<template>
  <div id="vue-receive-app">
    <p>Vue Micro frontend 2</p>
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  },
};
</script>

<style>
#vue-receive-app{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #333;
  margin-top: 10px;
  border: solid 1px #42b983;
  border-radius: 8px;
  padding-bottom: 10px;
}
</style>
