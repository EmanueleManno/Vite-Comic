<!--SCRIPT-->
<script>

//Importazione dei file:
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  data() {
    return {

    }
  },

  //Componenti:
  components: {
    AppHeader: AppHeader,
    AppMain: AppMain,
    AppFooter: AppFooter,
  }
}
</script>

<!--TEMPLATE-->
<template>
  <!--HEADER-->
  <AppHeader />

  <!--MAIN-->
  <AppMain />

  <!--FOOTER-->
  <AppFooter />
</template>

<!--STYLE-->
<style lang="scss">
/*CSS RESET*/
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/*GENERICS*/
body {
  font-family: 'Open Sans Condensed';

  /*UTILITIES*/
  .container {
    max-width: 1080px;
    margin: 0 auto;
  }
}
</style>