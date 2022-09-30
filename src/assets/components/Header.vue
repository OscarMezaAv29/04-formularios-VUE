<template>
    <div class="row">
      <div class="col-12">
        <h1>Formularios</h1>
      </div>
      <div class="col-12">
        <img width="100" :src="url" :alt="msg">
      </div>
    </div>
</template>

<script>
    export default {
      data: () => ({
        url: "https://cdn.svgporn.com/logos/vue.svg",
        msg: "Vue.js",
      }),
      methods: {
        addUser () {
          console.log(this.nombre, this.edad, this.correo);
        }
      }
    }
  </script>