<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink to="/" class="font-bold">Nuxt Dojo</NuxtLink>
        <ul class="flex gap-4">
          <li><Nuxt-link to="/">Home</Nuxt-link></li>
          <li><Nuxt-link to="/about">About</Nuxt-link></li>
          <li><Nuxt-link to="/products" class="btn">Products</Nuxt-link></li>
        </ul>
      </nav>
    </header>

    <!-- Output the page content -->
    <div class="container mx-auto p-4">
      <slot />
    </div>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
