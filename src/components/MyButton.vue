<script setup lang="ts">

const emit = defineEmits<{
  (event: 'add-something', param: number): void
}>()

</script>

<template>
  <button @click="emit('add-something', 1)">Add</button>
</template>