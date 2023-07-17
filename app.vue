<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<script lang="ts" setup>
useHead({
  titleTemplate: (title) => `${title}`,
  meta: [{ name: 'description', content: "TomovBlogs - Tech Research Blog - Martin Tomov" }],
  link: [{ rel: 'icon', type: 'image/png', href: `${useRuntimeConfig().app.baseURL}favicon.ico` }],
  htmlAttrs: { lang: "en" },
  bodyAttrs: { class: "bg-white dark:bg-black text-[#555555] dark:text-[#bbbbbb]" },
});
</script>
