<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <div class="container text-center">
    <nav class="my-4">
      <RouterLink to="/" class="nav-link" >Home </RouterLink>
      <RouterLink to="/about" class="nav-link"> About </RouterLink>
    </nav>

   <div class="d-flex justify-content-center"> <RouterView /></div>
  </div>
</template>

<style scoped>
a.nav-link {
  display: inline;
  color: black;
  border: white;
}
a.router-link-active {
  border: #3FB984 3px solid;
  color: black;
}
</style>
