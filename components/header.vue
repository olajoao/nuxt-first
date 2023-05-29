<template>
  <header class="header">
    <NuxtLink to="/"><h1>LOGO</h1></NuxtLink>
    <div class="right">
      <form class="search" @submit.prevent="">
        <input class="search__input" type="text" placeholder="Procurando algum produto específico?"/>
        <span class="search__icon">|||</span>
      </form>
    </div>
  </header>
</template>
<style scoped>
.header {
  align-items: center;
  background-color: #fff;
  display: flex;
  justify-content: space-between;
  padding: 1rem;
}

.right {
  align-items: center;
  display: flex;
  gap: 1rem;
}

.search {
  position: relative;
}

.search__input {
  background-color: #f1f1f1;
  border: 1px solid transparent;
  border-radius: 0.6rem;
  font-size: 1.4rem;
  outline: none;
  padding: 0.8rem 1rem;
  min-width: 30rem;
}

.search__input::placeholder {
  color: #a1a1a1;
}

.search__icon {
  position: absolute;
  inset-block: 0;
  margin-block: auto;
  right: 1rem;
  font-size: 15px;
  height: max-content;
}
</style>
