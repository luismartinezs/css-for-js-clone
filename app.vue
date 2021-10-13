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

<style lang="scss">
@import '~/assets/css/normalize.css';
@import '~/assets/css/theme.css';
@import '~/assets/css/base.css';
@import '~/assets/css/utility.css';
@import '~/assets/css/components.css';

body {
  font-family: "Roboto", Arial, Helvetica, sans-serif;
  font-size: 18px;
  height: 100%;
  background-color: var(--color-background);
}
</style>