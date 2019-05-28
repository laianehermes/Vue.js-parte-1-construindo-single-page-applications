<template>

  <div>
    <h1>{{ titulo }}</h1>

    <img v-for="foto in fotos" :src="foto.url" :alt="foto.titulo">

  </div>

</template>

<script>

export default {

  data () {
    return {
      titulo: "Alurapic",
      fotos: []

    }
  },
  created() {

    alert('Funcionou!');
  }
}
</script>
<style>
</style>