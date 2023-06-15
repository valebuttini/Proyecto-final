<template>
  <div id="app-component">
    <!-- <MiCompo/> -->
    <CatalogoPag>
      hola
    </CatalogoPag>

  </div>
</template>

<script>
// import MiCompo from './components/MiCompo.vue';
import CatalogoPag from './components/CatalogoPag.vue';

export default {
  name: 'App',
  components: {
    // MiCompo,
    CatalogoPag,
  },

};
</script>

<style>
#app-component {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
