<template>
  <h1>Hello App</h1>
  <p>
    <router-link to="/">Go to Home</router-link>
    <router-link to="/about">Go to About</router-link>
  </p>
  <router-view></router-view>
</template>

<script>

import axios from 'axios'
export default {
  name: 'App',
  components: {
    
  },
  setup() {
    return {
      getData(){
        axios.get("xx")
      }
    }
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
