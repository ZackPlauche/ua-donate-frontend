<template>
  <div>
    <h1>Hello World!</h1>
    {{ BASE_URL }}
  </div>
</template>

<script setup>
const BASE_URL = import.meta.env.BASE_URL
</script>