<template>
  <div id="app">
    <mind></mind>
  </div>
</template>

<script>

import Mind from './components/Mind'
export default {
  name: 'app',
  components: {
    Mind,
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
