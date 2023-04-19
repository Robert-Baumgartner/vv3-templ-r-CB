<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <div class="container text-center">
    <div class="my-4 d-flex justify-content-center">
      <RouterLink to="/" class="nav-link me-3" active-class="border-bottom border-3 border-primary"
        >Home</RouterLink>
      <RouterLink to="/about" class="nav-link" active-class="border-bottom border-3 border-primary">
        About
      </RouterLink>
    </div>

    <div class="d-flex justify-content-center"><RouterView /></div>
  </div>
</template>
