<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <MiComponente></MiComponente>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MiComponente from "./components/MiComponente.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    MiComponente,
  },
};
</script>

<style>
/*
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*/

@import "./assets/css/styles.css";
</style>
