<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HomePage msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    HomePage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
body {
  background-attachment: fixed;
  background: linear-gradient(to bottom, #555, #999);
}
main{
  min-height: 300px;
  width: 1400px;
  background-color: white;
margin: 0 auto;
}
</style>
