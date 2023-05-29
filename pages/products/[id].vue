<template>
  <h1>aasdfasdasd {{ id }}</h1>
  <NuxtLink to="/products">Go back</NuxtLink>
</template>
<script lang="ts" setup>
const { id } = useRoute().params;
</script>
