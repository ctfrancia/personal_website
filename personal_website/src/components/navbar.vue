<template>
  <div class='container'>

    <div class='Home'>Home</div>
    <div class='rest'>About Me</div>
    <div class='rest'>Blog</div>
    <div class='rest'>Porfolio and Resume</div>
    <div class='rest'>Contact</div>

  </div>
</template>

<script>
/* eslint-disable no-unused-vars */
/* eslint-disable-next-line */
/* eslint-disable */
import Vue from "vue";
import VueRouter from "vue-router";
//importing the components for the router
import Desktop from "desktop.vue";
import AboutMe from "About.vue";
import Blog from "Blog.vue";
import Contact from "Contact.vue";
import Home from "Home.vue";
import Portfolio from "Portfolio.vue";

//setting up the router
Vue.use(VueRouter);
const aboutMe = AboutMe;
const blog = Blog;
const contact = Contact;
const home = Home;
const portfolio = Portfolio;

const routes = [
  {path: '/aboutme', component:aboutMe },
  {path: '/blog', component:blog },
  {path: '/contact', component:contact },
  {path: '/home', component:home },
  {path: '/portfolio', component:portfolio }
];

const router = new VueRouter({
  routes: routes
  });
const app = new Vue({
  router
}).$mount('#app');
export default {
  name: "NavBar",
  data () {
    return {

    }
  }
};
</script>
<style scoped>
</style>
