<template>
  <div id="app">
    <img alt="logo" src="./assets/logo.png">
    <Translator />
  </div>
</template>

<script>
import Translator from './components/Translator.vue'

export default {
  name: 'App',
  components: {
    Translator
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
</style>
