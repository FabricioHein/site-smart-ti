<script setup>
import { ref } from 'vue'

defineProps({
  nome: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ nome }}</h1>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
