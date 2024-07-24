<script setup>
import Button from '../components/buttonError.vue'
</script>

<template>
  <main>
    <Button />
  </main>
</template>

<style>

main {
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

@media (min-width: 1024px) {
  main {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>


