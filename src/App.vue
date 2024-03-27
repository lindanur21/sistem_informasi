<template>
  <!-- <Navbar /> -->
  <br>
  <router-view></router-view>
  <Dashboard></Dashboard>
  <Footer></Footer>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Dashboard from './components/Dashboard.vue';
import Footer from './components/Footer.vue';
export default {
  components: {
    // Navbar,
    Dashboard,
    Footer,
  },
};
</script>