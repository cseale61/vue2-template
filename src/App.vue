<template>
  <div>
    <div id="app">
      <Navbar />

      </div>
      <router-view/>
  </div>
</template>

<script>
  import Navbar from './components/Navbar';
  export default {
    name: "app",
    components: {
      Navbar
    }
    
  }
</script>

<style lang="scss" scoped>

</style>