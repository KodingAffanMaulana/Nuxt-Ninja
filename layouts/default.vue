<template>
  <div>
    <header class="shadow-sm bg-white text-bold">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink to="/">Nuxt <span class="text-green-400">Ninja</span></NuxtLink>
        <ul class="flex gap-4 ">
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products" class="btn">Product</NuxtLink></li>
        </ul>
      </nav>
    </header>
  </div>
  <div  class="container mx-auto p-4"><slot /></div>
</template>

<script setup>

</script>

<style scoped>
.router-link-exact-active {
     color: aqua;
}
</style>
