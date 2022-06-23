<template>
  <div>
    <ol>
      <li v-for="i in 20">
        <NuxtLink :to="`/users/${i}`">User {{ i }}</NuxtLink>
      </li>
    </ol>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: "Users"
})
</script>