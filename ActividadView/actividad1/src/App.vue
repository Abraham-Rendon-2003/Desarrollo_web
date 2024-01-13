<template>
  <div id="app">
    <Navbar />
    <div class="container">
      <Sidebar />
      <router-view />
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Sidebar
  }
}
</script>

<style>
.container {
  display: flex;
}
</style>
