<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Title msg="La mia prima app con Vue CLI!" />
    <Hero msg="Il mio primo Jumbotron con Vue CLI!"/>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    Title,
    Hero,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
