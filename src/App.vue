<template>
  <div class="container mt-3">
    <Header />
    <Formulario />
  </div>
</template>

<script>
  import Header from "./assets/components/Header.vue";
  import Formulario from "./assets/components/Formulario.vue";

  export default {
    components: {
      Header,
      Formulario,
    }
  }
</script>
