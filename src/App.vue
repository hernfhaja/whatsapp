<template>
  <div id="app">
    <Whatsapp />
  </div>
</template>

<script>
import Whatsapp from "./components/Whatsapp.vue";

export default {
  name: "App",
  components: {
    Whatsapp,
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
