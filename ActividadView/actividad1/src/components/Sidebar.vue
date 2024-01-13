<template>
  <div class="sidebar bg-light">
    <ul>
      <li>
        <router-link to="/" class="nav-link">Inicio</router-link>
      </li>
      <li>
        <router-link to="/about" class="nav-link">Acerca de</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'AppSidebar'
}
</script>

<style scoped>
.sidebar {
  width: 250px;
  height: 100%;
  position: fixed;
  top: 0;
  left: 0;
  padding-top: 20px;
}

</style>
