<template>
  <main class="h-screen flex items-center justify-center"
  :style="{backgroundColor: `rgb(${red}, ${blue}, ${green})`}"
  >
    <div class="flex flex-col">
      <input type="number" placeholder="red" v-model="red">
      <input type="number" placeholder="blue" v-model="blue">
      <input type="number" placeholder="green" v-model="green">
    </div>
  </main>
</template>

<script setup>
import { ref } from 'vue'

const red = ref(0)
const blue = ref(0)
const green = ref(0)


</script>

<style scoped>
/* main {
  background-color: rgb(122, 50, 255);
} */
</style>