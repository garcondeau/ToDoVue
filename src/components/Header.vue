<script setup lang="ts">
import IconLogo from "./icons/IconLogo.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">
          <IconLogo class="logo"/>
        </RouterLink>
        <RouterLink to="/"> Home </RouterLink>
        <RouterLink to="/about"> About </RouterLink>
      </nav>
    </div>
  </header>
</template>

<style scoped>
header {
  background: #3b4252;
  padding: 10px 30px;
}
nav {
    display: flex;
    grid-gap: 10px;
}
.logo {
    width: 16px;
}
</style>
