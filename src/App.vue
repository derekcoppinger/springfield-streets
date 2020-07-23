<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/downtown_springfield_il.jpg">
    <most-popular-streets/>
  </div>
</template>

<script>
import MostPopularStreets from './components/MostPopularStreets.vue'

export default {
  name: 'App',
  components: {
    MostPopularStreets
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img {
  border-radius: 8px;
  width: 100%;
  height: auto;
}
</style>
