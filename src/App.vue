<template>
  <div id="app">
      <router-view/>
  </div>
</template>

<script>

import home from '@/views/Home.vue'

export default {
  name: "app",
  components: {
    home,

  }
}
</script>


<style lang="scss">

@import "./src/style/base";


#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
