<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <AppSidebar />
  <!-- <font-awesome-icon icon="fa-solid fa-user-secret" /> -->
</template>

<script>
import AppSidebar from "./components/AppSidebar.vue";
// import SidebarIcon from './components/SidebarIcon.vue'
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "App",
  components: {
    // HelloWorld,
    AppSidebar,
  },
};
</script>
