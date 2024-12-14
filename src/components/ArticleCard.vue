<script setup lang="ts">
import CategoryTag from "./CategoryTag.vue";
import Button from "./Button.vue";
</script>

<template>
  <article
    class="overflow-clip group rounded-lg w-[min(100%,340px)] mx-auto focus-within:outline-indigo-700 focus-within:ring isolate shadow bg-white"
  >
    <img
      src="/spacejoy-YqFz7UMm8qE-unsplash.jpg"
      width="340"
      height="288"
      alt=""
      decode="async"
      class="w-full aspect-[340/288] object-cover"
    />
    <div class="py-6 px-4">
      <ul class="flex items-center gap-1 relative z-10">
        <li>
          <CategoryTag href="#1"> Interior </CategoryTag>
        </li>
      </ul>
      <h3 class="font-bold text-lg mt-2 mb-3 text-balance">
        Top 5 Living Room Inspirations
      </h3>
      <p class="text-neutral-600 mb-6">
        Curated vibrants colors for your living, make it pop & calm in the same
        time.
      </p>
      <Button>
        Read more
        <svg
          width="14"
          height="14"
          viewBox="0 0 14 14"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          aria-hidden="true"
        >
          <path
            d="M10.4763 6.16658L6.00633 1.69657L7.18483 0.518066L13.6667 6.99992L7.18483 13.4817L6.00633 12.3032L10.4763 7.83325H0.333328V6.16658H10.4763Z"
            fill="currentColor"
          />
        </svg>
      </Button>
    </div>
  </article>
</template>
