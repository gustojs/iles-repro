<template>
  <button @click="click">click me</button>
  <div>counter is now {{ counter }}</div>
</template>

<script setup lang="ts">
import { ref } from "vue";
const counter = ref(0);
function click() {
  counter.value++;
}
</script>
