<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <h1 class="bg-cyan-500 px-4 py-4 rounded-md text-3xl text-white text-center">Welcome to Protidin</h1>
    <nav class="flex items-center justify-center gap-4 mt-10">
      <RouterLink to="/" class="underline">Home</RouterLink>
      <RouterLink to="/about" class="underline">About</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>
