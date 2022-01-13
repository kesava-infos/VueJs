<template>
  <div id="app">
    <Scroll />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import Scroll from "./components/scrollExample"
export default {
  name: "App",
  components: {
    Scroll
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
