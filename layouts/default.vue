<template>
  <div class="bg-red-400">
    Default Layout
    <TheSidebar />
    <div class="p-4 sm:ml-64">
      <slot />
    </div>
  </div>
</template>

<script setup>

import TheSidebar from "~/components/layout/TheSidebar.vue";

useHead({
  bodyAttrs: {
    class: 'bg-slate-700'
  }
})
</script>