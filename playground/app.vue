<template>
  <div>
    Nuxt module playground!
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
const { data } = await useFetch('/hello')
</script>
