<template>
<div>
  <TheHeader />
  <body>
    <TheHero />
    <TheIntro />
    <HighlightedTitle />
    <TrustedBrands />
    <SingleTestimonial />
  </body>
</div>
</template>

<script setup>
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

<style>
@import '~/assets/css/global.css';

body {
  background-color: var(--color-background);
}
</style>