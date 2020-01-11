<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to FTX's Vue.js App" />
    <test />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Test from './components/Test';

export default {
  name: 'app',
  components: {
    HelloWorld,
    Test
  }
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
