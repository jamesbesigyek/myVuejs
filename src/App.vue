<template>
  <div id="app">
    
    
    <AppBodyStructure/>
  </div>
</template>

<script>

import AppBodyStructure from './components/AppBodyStructure'


export default {
  name: 'app',
  components: {
    
    AppBodyStructure,
    

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
</style>
