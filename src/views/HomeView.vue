<template>
  <div class="container">
    <p>Pssst. This is the <span class="fw-bold">Home</span> view</p>
    <img src="@/assets/logo.svg" alt="Vue logo" height="100">
    <SayHello name="Robert"></SayHello>
  </div>
</template>

<script setup>
import SayHello from '@/components/SayHello.vue';
</script>
