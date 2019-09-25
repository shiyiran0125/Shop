<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Hello></Hello>
    <Fade></Fade>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Fade from './components/fade'
export default {
  name: 'App',
  components: {
    Hello,
    Fade
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
