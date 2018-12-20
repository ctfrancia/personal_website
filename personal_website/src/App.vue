
<template>
  <div id="app">
    <div class='container'>
      <Desktop/>
      <div class='navbar'>
      <router-link to="/home">Home</router-link>
      <router-link to="/aboutme">About Me</router-link>
      <router-link to="/blog">Blog</router-link>
      <router-link to="/portolio">Portfolio and Resume</router-link>
      <router-link to="/contact">Contact</router-link>
      </div>
    </div>

  </div>
</template>

<script>
// /* eslint-disable no-unused-vars */
// /* eslint-disable-next-line */
// /* eslint-disable */
import Desktop from "./components/desktop.vue";
// import Vue from "vue";
// import VueRouter from "vue-router";
// //importing the components for the router
// import AboutMe from "./components/About.vue";
// import Blog from "./components/Blog.vue";
// import Contact from "./components/Contact.vue";
// import Home from "./components/Home.vue";
// import Portfolio from "./components/Portfolio.vue";

// //setting up the router
// Vue.use(VueRouter);
// const aboutMe = AboutMe;
// const blog = Blog;
// const contact = Contact;
// const home = Home;
// const portfolio = Portfolio;

// const routes = [
//   {path: '/aboutme', component:aboutMe },
//   {path: '/blog', component:blog },
//   {path: '/contact', component:contact },
//   {path: '/home', component:home },
//   {path: '/portfolio', component:portfolio }
// ];

// const router = new VueRouter({
//   routes: routes
//   });
// const app = new Vue({
//   router
// }).$mount('#app');

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
</style>
