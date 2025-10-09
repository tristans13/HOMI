<script setup lang="ts">

</script>

<template>
  <header class="w-full h-[90px] flex items-center justify-between px-10 bg-background border-b border-border shadow-md">
    <div class="flex items-center space-x-8">
      <img src="/assets/HOMI LOGO 1.png" alt="HOMI Logo" class="h-10 w-auto object-contain" />

    </div>
    <div class="flex items-center space-x-15">
      <NuxtLink class="uppercase" active-class="underline text-blue-500 font-semibold" to="/">Home</NuxtLink>
      <NuxtLink class="uppercase" active-class="underline text-blue-500 font-semibold" to="/features">Features</NuxtLink>
      <NuxtLink class="uppercase" active-class="underline text-blue-500 font-semibold" to="/solutions">Solutions</NuxtLink>
      <NuxtLink class="uppercase" active-class="underline text-blue-500 font-semibold" to="/pricing">Pricing</NuxtLink>
    </div>

    <div class="flex items-center space-x-1">
      <Button variant="ghost">Login</Button>
      <Button class="w-26">Signup</Button>
    </div>

  </header>
</template>