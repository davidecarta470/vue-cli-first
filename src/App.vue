<template>
  <div >
    <Header/>
    <Main/>
    <h1>Io sono l'h1 presente nell'App</h1>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style>
h1{
  text-align:center;
  color:blue
}
.background-aquamarine{
  background-color:aquamarine;
}

</style>
