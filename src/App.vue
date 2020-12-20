<template>
  <div>
    <link href='https://fonts.googleapis.com/css?family=Source+Sans+Pro' rel='stylesheet' type='text/css'>
    <startscreen />

  </div>

</template>

<script>
  import startscreen from './components/startscreen.vue'
  import Vue from 'vue'
  import {
    BootstrapVue,
  } from 'bootstrap-vue'

  Vue.use(BootstrapVue)


  export default {
    name: 'App',
    components: {
      startscreen
    }
  }
</script>

<style>
  html,
  body {
    margin: 0px;
    padding: 0px;
  }

  #app {
    font-family: Source Sans Pro;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin: 0px;

  }
</style>