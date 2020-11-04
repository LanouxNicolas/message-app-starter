<template>
  <div class="app">
    <Menu :unreadMessages="42"/>
    <Messages/>
  </div>
</template>

<script>
import Menu from "./components/Menu.vue";
import Messages from "./components/Messages.vue";

export default {
  name: "App",
  components: {
    Menu,
    Messages
  }
};
</script> 

<style>
html, body {
  height: 100%;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
