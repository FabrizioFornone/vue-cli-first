<template>
  <div id="app">
    <phrase />
    <hero />
  </div>
</template>

<script>
import phrase from "./components/phrase.vue";
import hero from "./components/hero.vue";

export default {
  name: "App",
  components: {
    phrase,
    hero,
  },
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #231f20;
}
</style>
