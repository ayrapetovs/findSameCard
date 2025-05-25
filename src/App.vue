<script setup>
import { ref } from 'vue';
const today = ref(new Date().toLocaleDateString('ru-RU'));
</script>


<template>
  {{ today }}
</template>

<style scoped>
</style>