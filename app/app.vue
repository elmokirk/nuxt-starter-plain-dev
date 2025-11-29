<script setup lang="ts">
  const config = useRuntimeConfig();
</script>

<template>
  <div>
    <h1>Hello World!</h1>
    <h2>This is a Test for public Environment Variables: {{ config.public.testVar }}</h2>
  </div>
</template>
