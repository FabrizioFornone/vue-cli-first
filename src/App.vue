<template>
  <div id="app">
    <phrase />
  </div>
</template>

<script>
import phrase from './components/phrase.vue'

export default {
  name: "App",
  components: {
    phrase
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
