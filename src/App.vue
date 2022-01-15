<template>
  <div id="app">
    <home />
  </div>
</template>

<script>
import Home from "./views/home/Home.vue";
export default {
  name: "App",
  data() {
    return {
      message: "Hello World"
    };
  },
  components: {
    Home
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  overflow: hidden;
}
</style>
