<script setup lang="ts">
const { href } = defineProps<{ href: string }>();
</script>

<template>
  <a
    class="rounded-full border border-green-200 text-green-700 py-0.5 px-2 text-center bg-green-50 focus-outline-green-700 focus-visible:outline-green-700 hover:bg-green-100 text-sm"
    :href="href"
  >
    <slot />
  </a>
</template>
