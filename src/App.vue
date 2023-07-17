<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <ComponentHome msg="Welcome to Your Vue.js App" />
  <ComponentAbout msg="About us page"/>
</template>

<script>
import ComponentHome from "./components/ComponentHome.vue";
import ComponentAbout from "./components/ComponentAbout.vue";



export default {
  name: "App",
  components: {
    ComponentHome,
    ComponentAbout
  },
};
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
