<template>
  <div class="app">
    <Menu :unreadMessages="42"/>
    <Messages/>
    <Message/>
  </div>
</template>

<script>
import Menu from "./components/Menu.vue";
import Messages from "./components/Messages.vue";
import Message from "./components/Message.vue";

export default {
  name: "App",
  components: {
    Menu,
    Messages,
    Message
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
