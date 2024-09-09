<script setup>
const nome = "Murata"

const meuObj = {
  nome: "Guilherme Murata",
  filmeFav: "Openheimer"
}

function dizOla(nome) {
  return `${nome} diz oi`;
}
</script>

<template>
  <h1>
    {{ dizOla("Paula") }}
  </h1>
</template>

<style scoped>
</style>
