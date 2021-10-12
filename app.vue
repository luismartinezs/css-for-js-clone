<template>
<div>
  <TheHeader />
  <body>
    <TheHero />
  </body>
</div>
</template>

<script setup>
import TheHeader from "@/components/TheHeader.vue";

useMeta({
  title: "CSS for JS Clone",
  link: [
    {
      rel: "preconnect",
      href: "https://fonts.googleapis.com",
    },
    {
      rel: "preconnect",
      href: "https://fonts.gstatic.com",
      crossorigin: true,
    },
    {
      rel: "stylesheet",
      href: "https://fonts.googleapis.com/css2?family=Roboto&display=swap",
    },
  ],
});
</script>


