<template>
  <List />
  <h1>aasdfasdasd {{ id }}</h1>
  <NuxtLink to="/products">Go back</NuxtLink>
</template>
<script lang="ts" setup>
import List from './list.vue';
const { id } = useRoute().params;
</script>
