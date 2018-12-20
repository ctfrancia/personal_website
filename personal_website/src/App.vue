
<template>
  <div id="app">
    <div class='container'>
      <Desktop/>
      <div class='navbar'>
        <p>
          <router-link to="/home">Home</router-link>
          <router-link to="/aboutme">About Me</router-link>
          <router-link to="/blog">Blog</router-link>
          <router-link to="/portolio">Portfolio and Resume</router-link>
          <router-link to="/contact">Contact</router-link>
        </p>
      </div>
    </div>

  </div>
</template>

<script>
// /* eslint-disable no-unused-vars */
// /* eslint-disable-next-line */
// /* eslint-disable */
import Desktop from "./components/desktop.vue";

export default {
  name: "app",
  components: {
    Desktop
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
.navbar {
  display: flex;
}
</style>
