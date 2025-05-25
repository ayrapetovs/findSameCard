<script setup>
import { ref } from 'vue'

const today = ref(new Date().toLocaleDateString('ru-RU'))
</script>

<template>
  <p>Сегодня: {{ today }}</p>
</template>

<style scoped></style>