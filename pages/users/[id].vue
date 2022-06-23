<template>
  <h1>User {{ $route.params.id }}</h1>
</template>

<script setup lang="ts">
const route = useRoute()

useHead({
  title: `User ${route.params.id}`
})
</script>