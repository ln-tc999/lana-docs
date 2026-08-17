<script setup lang="ts">
import { ref, onMounted } from 'vue'

const mounted = ref(false)

onMounted(() => {
  mounted.value = true
})
</script>

<template>
  <section
    class="relative w-full h-screen min-h-[700px] max-h-[1080px] overflow-hidden flex flex-col justify-between pt-20 pb-6 sm:pb-8 px-6 md:px-12 lg:px-16 font-sans select-none bg-neutral-950 text-white dark:bg-[#0a0a0a]"
  >
    <!-- BACKGROUND & NATURAL ASPECT-RATIO CENTER PORTRAIT -->
    <div class="absolute inset-0 z-0 overflow-hidden pointer-events-none flex items-center justify-center">
      <div class="relative h-[62vh] sm:h-[68vh] md:h-[72vh] max-h-[640px] w-auto aspect-[3/4] rounded-3xl overflow-hidden shadow-2xl border border-white/10 mt-2">
        <img
          src="/image-me.webp"
          alt="Muhammad Maulana Firdaussyah"
          class="w-full h-full object-cover object-top opacity-95"
        />
      </div>
      <div class="absolute inset-0 bg-gradient-to-t from-[#0a0a0a] via-[#0a0a0a]/30 to-transparent z-10" />
    </div>

    <!-- TOP ROW: SERVICES (LEFT) & SOCIAL CLUSTER (RIGHT) -->
    <div class="relative z-20 w-full flex flex-row items-start justify-between gap-4 pt-4">
      <div class="text-xs sm:text-sm font-medium tracking-wide text-white/90 leading-relaxed space-y-1 drop-shadow-md">
        <p>Fullstack Developer /</p>
        <p>Web3 Developer /</p>
        <p>AI Engineering /</p>
        <p class="text-white/60">Digital Systems & Finance</p>
      </div>

      <div class="grid grid-cols-2 gap-2 flex-shrink-0">
        <a
          href="https://github.com/maulana-tech"
          target="_blank"
          rel="noopener noreferrer"
          title="GitHub"
          class="w-10 h-10 sm:w-12 sm:h-12 rounded-full bg-[#000000] text-white flex items-center justify-center shadow-xl border border-white/20 hover:scale-105 transition-transform"
        >
          <UIcon name="i-simple-icons-github" class="w-5 h-5 sm:w-6 sm:h-6" />
        </a>

        <a
          href="https://linkedin.com/in/muhammad-maulana-firdaussyah-083362293"
          target="_blank"
          rel="noopener noreferrer"
          title="LinkedIn"
          class="w-10 h-10 sm:w-12 sm:h-12 rounded-full bg-[#0057ff] text-white flex items-center justify-center shadow-xl border border-white/20 hover:scale-105 transition-transform"
        >
          <UIcon name="i-simple-icons-linkedin" class="w-5 h-5 sm:w-6 sm:h-6" />
        </a>

        <a
          href="https://instagram.com/lana.dev_"
          target="_blank"
          rel="noopener noreferrer"
          title="Instagram"
          class="w-10 h-10 sm:w-12 sm:h-12 rounded-full bg-[#ea4c89] text-white flex items-center justify-center shadow-xl border border-white/20 hover:scale-105 transition-transform"
        >
          <UIcon name="i-simple-icons-instagram" class="w-5 h-5 sm:w-6 sm:h-6" />
        </a>

        <a
          href="https://x.com/developerlana0"
          target="_blank"
          rel="noopener noreferrer"
          title="X (Twitter)"
          class="w-10 h-10 sm:w-12 sm:h-12 rounded-full bg-black text-white flex items-center justify-center shadow-xl border border-white/20 hover:scale-105 transition-transform"
        >
          <UIcon name="i-simple-icons-x" class="w-5 h-5 sm:w-6 sm:h-6" />
        </a>
      </div>
    </div>

    <!-- BOTTOM ROW -->
    <div class="relative z-20 w-full flex flex-col justify-end pb-2">
      <div class="mb-1 sm:mb-2">
        <span class="text-sm sm:text-base md:text-lg font-medium text-white/90 tracking-wide drop-shadow-md">
          Hey! I'm...
        </span>
      </div>

      <div class="w-full relative flex items-baseline justify-between">
        <div class="flex flex-col">
          <h1 class="text-[12vw] sm:text-[10vw] md:text-[8vw] lg:text-[7vw] font-bold leading-[0.8] tracking-tighter text-transparent bg-clip-text bg-gradient-to-br from-white to-white/70 drop-shadow-lg uppercase">
            MAULANA
          </h1>
          <div class="flex items-center gap-2 sm:gap-3 mt-2 sm:mt-4">
            <span class="text-xs sm:text-sm font-medium tracking-widest text-white/50 uppercase">
              Yogyakarta, ID
            </span>
          </div>
        </div>

        <div class="hidden sm:flex self-end mb-2 sm:mb-4">
          <UButton
            to="/getting-started"
            color="white"
            variant="solid"
            class="rounded-full px-6 py-3 font-semibold group flex items-center gap-2"
          >
            Explore Docs
            <UIcon name="i-lucide-arrow-right" class="w-4 h-4 group-hover:translate-x-1 transition-transform" />
          </UButton>
        </div>
      </div>

      <!-- Mobile CTA -->
      <div class="sm:hidden w-full mt-6">
        <UButton
          to="/getting-started"
          color="white"
          variant="solid"
          block
          class="rounded-full py-3 font-semibold flex items-center justify-center gap-2"
        >
          Explore Docs
          <UIcon name="i-lucide-arrow-right" class="w-4 h-4" />
        </UButton>
      </div>
    </div>
  </section>
</template>
