<script setup lang="ts">

</script>

<template>
  <header class="w-full h-[90px] flex items-center justify-between px-10 bg-background border-b border-border">
    <div class="flex items-center space-x-8">
      <img
        src="/assets/HOMI LOGO 1.png"
        alt="HOMI Logo"
        class="h-10 w-auto object-contain"
      />

    </div>
    <div class="flex items-center space-x-8">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/features">Features</NuxtLink>
        <NuxtLink to="/solutions">Solutions</NuxtLink>
        <NuxtLink to="/pricing">Pricing</NuxtLink>
    </div>

    <div class="flex items-center space-x-4">
      <Button variant="ghost">Login</Button>
      <Button class="w-96px ">Sign Up</Button>
    </div>

  </header>
</template>

<style scoped>
header {
  font-family: 'Inter', sans-serif;
  letter-spacing: 0.02em;
}

img {
  display: inline-block;
  vertical-align: middle;
}
</style>