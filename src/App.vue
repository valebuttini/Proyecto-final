<template>
  <div id="app-component">
    <MiCompo/>
    <CatalogoApp/>

  </div>
</template>

<script>
import MiCompo from './components/MiCompo.vue';
import CatalogoApp from './components/CatalogoApp.vue';

export default {
  name: 'App',
  components: {
    MiCompo,
    CatalogoApp,
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
