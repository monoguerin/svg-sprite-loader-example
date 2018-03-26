<template>
  <div id="app">
    <twitter-icon />
    <router-view/>
  </div>
</template>

<script>
import TwitterIcon from './assets/sprite.svg?twitter-icon'

export default {
  name: 'App',
  components: {
    TwitterIcon
  }
}
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

svg {
  max-width: 200px;
}
</style>
