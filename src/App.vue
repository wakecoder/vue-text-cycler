<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <test-app msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import testApp from './components/test-app.vue'

export default {
  name: 'app',
  components: {
    testApp
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
