<script setup>
import { ref } from 'vue';
const today = ref(new Date().toLocaleDateString('ru-RU'));
</script>


<template>
  <time :datetime="today">{{ today }}</time>
</template>

<style scoped>
</style>