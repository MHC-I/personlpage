<template>
  <div>
  

    <Nuxt />


  
  </div>
</template>

<style lang="postcss">
html {
  font-family: sans-serif;
}
body {
  @apply bg-gray-100 m-4 md:mx-12 lg:m-0 xl:mx-28 lg:mx-16 lg:flex items-center;
  min-height: 100vh;
}
h1 {
  @apply mb-1 text-xl font-medium;
}
h2 {
  @apply text-lg font-medium;
}
p {
  @apply text-base text-gray-800 leading-6;
}
svg,
img {
  @apply select-none;
}
a {
  @apply text-gray-800 hover:underline select-none;
}
</style>

<script>
export default {
  head() {
    return {
      htmlAttrs: {
        class:
          "scrollbar-thin scrollbar-track-transparent scrollbar-thumb-gray-400",
      },
    };
  },
};
</script>