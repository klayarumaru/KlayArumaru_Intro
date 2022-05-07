<template>
  <div id="app">
    <MainIndex/>
  </div>
</template>

<script>
import MainIndex from './components/MainIndex.vue'

export default {
  name: 'App',
  components: {
    MainIndex
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0px;
  padding: 0px;
}
body {
  margin: 0;
  padding: 0;
}
</style>
