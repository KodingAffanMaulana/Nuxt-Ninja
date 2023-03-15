<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4 text-green-500">
        <NuxtLink to="/">Nuxt Ninja</NuxtLink>
      </nav>
    </header>
  </div>

  <div class="container mx-auto p-4">
    <slot />
  </div>

  <footer class="container mx-auto p-4 flex justify-between border-t-2">
    <ul class="flex gap-4">
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/about">About</NuxtLink></li>
      <li><NuxtLink to="/products">Product</NuxtLink></li>
    </ul>
  </footer>
</template>

<script setup></script>

<style scoped></style>
