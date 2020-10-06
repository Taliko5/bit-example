<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <CardTwo></CardTwo>
    <ProgressBar></ProgressBar>
    <p></p>
    <Spinner></Spinner>
    <p></p>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import CardTwo from './components/CardTwo.vue';
import ProgressBar from './components/elements/ProgressBar.vue';
import Spinner from './components/elements/Spinner.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    CardTwo,
    ProgressBar,
    Spinner,
  },
};
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

p {
    margin: 50px 0 50px;
  }
</style>
