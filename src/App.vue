<template>
  <div id="app">
    <a-navbar/>
    <router-view/>
  </div>
</template>

<script>
import ANavbar from '@/components/NavBar.vue'

export default {
  name: 'App',
  components: {
    ANavbar
  },
}
</script>
