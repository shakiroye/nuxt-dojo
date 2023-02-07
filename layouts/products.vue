<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4">
        <NuxtLink to="/products" class="font-bold">Nuxt Dojo Merch</NuxtLink>
      </nav>
    </header>

    <!-- Output the page content -->
    <div class="container mx-auto p-4">
      <slot />
    </div>

    <footer class="container mx-auto p-4 flex justify-between border-t-2">
      <ul class="flex gap-4">
        <li><Nuxt-link to="/">Home</Nuxt-link></li>
        <li><Nuxt-link to="/about">About</Nuxt-link></li>
        <li><Nuxt-link to="/products">Products</Nuxt-link></li>
      </ul>
    </footer>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
