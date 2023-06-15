<template>
    <div class="hello">
        <h1>Bienvenidos a buestro catalogo</h1>
        <p class="card">Carne a la olla con papas {{ imagen }} {{ informacion }}</p>
        <button @click="nuevoPlato">Añadir nuevo plato</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CatalogoApp',
  props: {
    imagen: {
      type: String,
      default: 'hola',
    },
  },
  data() {
    return {
      par: 'f',
      informacion: ['Santiago', 'Andrés', 'Fidel', 'Carolina'],
    };
  }

  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>


  </style>gvb