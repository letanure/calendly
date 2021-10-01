<script setup>
import { ref } from 'vue'

defineProps({
  title: String,
  desc: String,
  url: String
})

const count = ref(0)
</script>

<template>
  <div class="card">
      <div class="card-title">{{title}}</div>
      <div class="card-desc">{{desc}}</div>
      <a :href="url" target="_blank" rel="noopener noreferrer">Select</a>
  </div>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
