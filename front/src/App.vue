<script>
import LoginVue from './components/Login.vue';
import Navbar from './components/Navbar.vue'

export default {
  name: "App",
  components: {
    LoginVue,
    Navbar
  }
}
</script>

<template>
  <Navbar />
  <router-view></router-view>
</template>

<style scoped>


</style>
