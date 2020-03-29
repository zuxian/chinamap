<template>
  <div id="app">
    <ChinaMap msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import ChinaMap from './components/mapchinacomp.vue'

export default {
  name: 'App',
  components: {  ChinaMap  }
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
