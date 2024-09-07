<script lang="ts" setup>
function onClick() {
  throw new Error("Oh no!");
}
</script>

<template>
  <button @click="onClick">Click me</button>
</template>
