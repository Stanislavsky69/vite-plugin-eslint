<template>
  <div class="root">{{ title }}</div>
</template>

<script setup>
import { ref } from 'vue'

const title = ref('vue-js')
</script>

<style scoped>
.root {
  font-size: 18px;
}
</style>
