<template>
  <fall-banner></fall-banner>
</template>

<script>
import FallBanner from './components/FallBanner.vue'

export default {
  components: { FallBanner },
  name: 'App',
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
