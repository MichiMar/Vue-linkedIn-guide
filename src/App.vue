<template>
  <MiComponente />
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import MiComponente from './components/miComponente.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    MiComponente
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
