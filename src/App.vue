<template>
  <div id="app">
    <Quiz />
  </div>
</template>

<script>
import Quiz from './views/Quiz'

export default {
  name: 'app',
  components: {
    Quiz
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
}
</style>
