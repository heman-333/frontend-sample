<template>
  <div class="container">
    <h1>Hello from Nuxt 🚀</h1>

    <p>
      This is a simple frontend project for learning GitHub Actions CI.
    </p>

    <button @click="message = 'GitHub Actions CI is working!'">
      Test CI
    </button>

    <p v-if="message" class="success">
      {{ message }}
    </p>
  </div>
</template>

<script setup lang="ts">
const message = ref("")
</script>

<style>
.container {
  max-width: 800px;
  margin: 100px auto;
  padding: 20px;
  text-align: center;
  font-family: Arial, sans-serif;
}

h1 {
  font-size: 40px;
}

button {
  padding: 12px 24px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  font-size: 16px;
}

.success {
  margin-top: 20px;
  font-weight: bold;
}
</style>
