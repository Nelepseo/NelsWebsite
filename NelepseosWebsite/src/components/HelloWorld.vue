<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="text-center font-medium text-4xl mt-2.5">
    <h1 style="color: black">{{ msg }}</h1>
  </div>
</template>
