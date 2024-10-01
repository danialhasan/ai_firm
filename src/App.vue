<template>
  <div class="app">
    <nav class="bg-gray-800 p-4">
      <router-link to="/" class="text-white mr-4">Home</router-link>
      <router-link to="/about" class="text-white">About</router-link>
    </nav>
    <router-view></router-view>
  </div>
</template>

<script setup lang="ts">
</script>
