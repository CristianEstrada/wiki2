<template>
  <div id="app">
    
    <home_navbar/>
    <index_home/>
    
  </div>
</template>

<script>

import home_navbar from './components/home_navbar.vue'
import index_home from './components/index.vue'

export default {
  name: 'App',
  components: {
    home_navbar,
    index_home
  }
}
</script>

<style>

</style>
