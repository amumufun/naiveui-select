<script setup>
import { NSelect } from 'naive-ui'
import { ref } from 'vue';

const value = ref(null);
const options = [
  { label: 'Option 1', value: 'option1' },
  { label: 'Option 2', value: 'option2' },
  { label: 'Option 3', value: 'option3' },
  { label: 'Option 4', value: 'option4' },
  { label: 'Option 5', value: 'option5' },
  { label: 'Option 6', value: 'option6' },
  { label: 'Option 7', value: 'option7' },
  { label: 'Option 8', value: 'option8' },
  { label: 'Option 9', value: 'option9' },
];
</script>

<template>
  <div class="container">
    <n-select v-model:value="value" :options="options" />
  </div>
</template>

<style scoped>
html {
  background-color: #ccc;
}
.container {
  position: fixed;
  top: 100px;
  left: 100px;
  width: 400px;
  height: 200px;
  padding: 20px;
  background-color: #ffffff;
  border: 1px solid #ccc;
  border-radius: 10px;
  overflow: hidden;
  z-index: 3000;
}
</style>
