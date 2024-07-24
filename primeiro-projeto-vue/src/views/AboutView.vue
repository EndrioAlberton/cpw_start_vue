<script setup>
import Button from '../components/buttonError.vue'
</script>
<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Button />
  </div>
</template>

<style>

.about {
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
