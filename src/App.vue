<template>
  <Navbar :logo="logo_src" :alt="app_name" />
  <router-view />
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Navbar,
    Footer,
  },
  data() {
    return {
      logo_src: require("../public/img/logo.png"),
      app_name: "Make of Burguer",
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  font-family: Inter, Helvetica, sans-serif;
  box-sizing: border-box;
}

.main-container {
  margin: 50px;
  min-height: 250px;
}

h1 {
  font-size: 42px;
  text-align: center;
  margin-bottom: 30px;
  color: #222;
}
</style>
