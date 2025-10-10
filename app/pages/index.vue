<template>
  <NuxtLayout name="homi-layout">
    <div class="bg-[#F7F7F7]">
      <section
        class="relative w-screen h-[800px] bg-cover bg-no-repeat bg-center flex items-start pt-[120px]"
        style="background-image: url('/RectangleHome.png')"
      >
        <!-- Add z-index to background overlay so it's behind everything -->
        <div class="absolute inset-0 bg-white/0 -z-10"></div>
        <div class="max-w-[608px] ml-[130px] text-left">
          <h1
            class="font-inter font-bold text-[64px] leading-none tracking-[0] text-center"
          >
            <span
              class="text-blue-500 font-inter font-black text-[64px] leading-none tracking-[0] text-center"
              >HOMI</span
            >
            Designed for <br />
          </h1>
          <h1
            class="font-inter font-bold text-[64px] leading-none tracking-[0] text-left"
          >
            Modern Stays.
          </h1>
          <p
            class="font-[200] font-inter text-[28px] leading-[109%] tracking-[0] mt-5 not-italic text-black"
          >
            Future-ready. Guest-centric. Where<br />
            comfort meets innovation.
          </p>
          <div class="flex items-center space-x-5 mt-8">
            <input
              type="email"
              placeholder="Enter your email"
              class="w-[343px] h-[56px] px-4 text-black placeholder-gray-500 bg-transparent border border-black/50 rounded-[5px] focus:outline-none focus:ring-2 focus:ring-blue-400"
            />
            <button
              class="w-[228px] h-[55px] rounded-[5px] bg-blue-500 hover:bg-blue-600 text-white text-lg font-medium transition font-inter italic text-[24px] leading-none tracking-[0] text-center"
            >
              Sign up - it’s free
            </button>
          </div>
          <div class="w-[192px] border-t border-black opacity-0"></div>
          <p
            class="text-[16px] text-black mt-10 font-inter font-normal leading-none tracking-[0%] text-left"
          >
            By entering my email, I acknowledge the
            <a href="#" class="text-blue-500 hover:underline cursor-pointer">
              HOMI PRIVACY POLICY
            </a>
          </p>
        </div>
      </section>
      <div class="relative h-screen">
        <div class="h-[20%] absolute top-60 left-0 w-full bg-transparent"></div>
        <div
          class="h-[70%] absolute top-70 left-0 w-full bg-[url('/Rectangle33.png')] bg-cover bg-center bg-no-repeat"
        ></div>
        <div class="absolute top-8 w-full">
          <div>
            <section
              class="relative z-20 flex flex-col items-center justify-center bg-white rounded-[20px] shadow-lg py-[60px] h-[730px] mx-auto max-w-7xl w-7xl overflow-hidden"
            >
              <h2
                class="font-poppins font-semibold text-[44px] leading-[180%] tracking-[0em] text-center"
              >
                Why
                <span
                  class="font-poppins font-bold text-[44px] leading-[180%] tracking-[0em] text-center text-[#388FF0]"
                  >HOMI?</span
                >
              </h2>
              <p
                class="font-poppins font-normal text-[24px] leading-[180%] tracking-[0.02em] text-center text-[#696984]"
              >
                HOMI is an all-in-one Hotel Management Information System built
                to streamline hotel operations, elevate guest experiences, and
                boost efficiency. Whether through web, mobile app, or
                self-service kiosks, HOMI ensures every stay is seamless—from
                booking to check-out.
              </p>

              <div class="relative w-full h-[800px] mt-10">
                <img
                  src="/Group22.png"
                  alt="Group22"
                  class="absolute w-[540px] h-[360px] rounded-[20px] opacity-100"
                  style="top: 0px; left: 60px"
                />
                <img
                  src="/Group23.png"
                  alt="Group23"
                  class="absolute w-[540px] h-[360px] rounded-[20px] opacity-100"
                  style="top: 0px; left: 690px"
                />
              </div>
            </section>
          </div>
        </div>
      </div>
    </div>
  </NuxtLayout>
</template>
