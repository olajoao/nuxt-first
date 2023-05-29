<template>
  <ul>
    <li>
      <NuxtLink to="/products/1" activeClass="active__link">1 teste</NuxtLink>
    </li>
    <li><NuxtLink to="/products/2" activeClass="active__link">2</NuxtLink></li>
  </ul>
</template>
<script lang="ts" setup>
</script>
<style scoped>
.active__link {
  text-decoration: none;
  color: red;
}
</style>