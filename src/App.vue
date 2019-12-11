<template>
  <div>
    <navbar/>
    <router-view/>
  </div>
</template>

<script>
  import store from './store'
  import Navbar from './views/shared/_navbar'
  export default {
    components: {
      navbar: Navbar
    }
  }
</script>