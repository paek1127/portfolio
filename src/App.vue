<template>
  <headerComponent>1</headerComponent>
  <footerComponent></footerComponent>
</template>

<script>
import headerComponent from './components/header.vue';
import footerComponent from './components/footer.vue';

export default {
  name: 'App',
  components: {
    headerComponent,
    footerComponent,
  },
};
</script>

<style lang="scss" scoped>
footer {
  background-color: blue;
  ::v-deep {
    span {
      color: red;
    }
  }
}
</style>
