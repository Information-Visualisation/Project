<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <nav class="d-flex flex-column">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/foodgroup/fruits">Fruits</RouterLink>
        <RouterLink to="/subfoodgroup/red-fruits">Red Fruits</RouterLink>
        <RouterLink to="/food/apple">Apple</RouterLink>
      </nav>
  </main>
</template>
