<template>
  <header><h1 class="background-aquamarine">Io sono l'h1 del componente Header con style scoped 'color : red' e il colore dello sfondo l'ho aquisito da una classe generica in App</h1></header>
</template>

<script>
export default {
 name:'Header'
}
</script>

<style scoped>
h1{
  color:red;
}
</style>