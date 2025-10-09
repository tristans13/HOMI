<script setup lang="ts">

</script>

<template>
  <footer class="bg-[#1F1F1F] text-white">
    <div class="max-w-7xl mx-auto px-6 py-16 grid grid-cols-1 md:grid-cols-3 gap-12">
      <div class="space-y-6">
        <img src="/assets/HOMI LOGO 1.png" alt="HOMI Logo" class="h-10" />
        <p class="text-gray-400 text-sm leading-relaxed">
          Get started neow try our product
        </p>
        <div>
          <p class="text-left md:text-left text-white text-xs w-full">
            © 2025 CuSKTech Solution. Copyright and rights reserved
          </p>
        </div>
      </div>
      <div class="relative w-[851px] h-[60px]">
        <input type="email" placeholder="Enter your email here"
          class="w-full h-full pl-6 pr-20 text-white bg-transparent border-2 border-white/70 rounded-[70px] placeholder-white/60 focus:outline-none" />
        <button
          class="absolute right-[7px] top-[7px] w-[46px] h-[46px] flex items-center justify-center rounded-full bg-blue-400 text-white hover:bg-gray-200 transition">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
            stroke-linecap="round" stroke-linejoin="round" class="w-[24px] h-[24px]">
            <path d="M5 12h14" />
            <path d="M12 5l7 7-7 7" />
          </svg>
        </button>
        <div class="mt-10 text-right space-x-4 space-y-10 text-xs text-white w-full">
          <a href="#" class="hover:text-white transition">Terms and Conditions</a>
          <span>·</span>
          <a href="#" class="hover:text-white transition">Privacy Policy</a>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>