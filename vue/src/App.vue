<template>
  <div id="app">
    <Header />
    <HelloWorld />
    <Home />
    <Footer />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Home from './components/Home.vue';
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';


export default {
  name: 'App',
  components: {
    HelloWorld,
    Home,
    Header,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
