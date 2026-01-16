<template>
  <div class="slow-component-loaded">
    Slow component loaded!
  </div>
</template>

<script setup lang="ts">
// Introduce a small delay to simulate a slow loading component
await new Promise(resolve => setTimeout(resolve, 100))
</script>
