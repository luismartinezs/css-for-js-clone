<template>
  <div class="flex jcc aic flex-col">
    <div class="spacer"></div>
    <h1 class="hero-title">Stop wrestling with CSS.</h1>
    <div class="spacer"></div>
    <h2
      class="hero-subtitle"
    >The all-new interactive learning experience designed to help JavaScript developers become confident with CSS.</h2>
    <div class="spacer-big"></div>
    <div class="flex jcc aic avatar">
      <img
        src="~/assets/images/me-avatar.jpg"
        alt="A very handsome fella with swoopy hair"
        class="avatar__img"
      />
      <span>
        Taught by
        <span>Luis Martinez</span>
      </span>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.hero-title {
  font-size: min(72px, 8vw);
  font-weight: 500;
  width: max-content;
  text-align: center;
  background-color: rgb(255, 178, 62);
  background-image: linear-gradient(
    268.67deg,
    rgb(255, 255, 255) 3.43%,
    rgb(255, 240, 102) 15.69%,
    rgb(255, 163, 26) 55.54%,
    rgb(255, 0, 115) 99%
  );
  background-size: 100%;
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
}

.hero-subtitle {
  font-size: 30px;
  font-weight: 300;
  max-width: 818px;
  text-align: center;
}

.avatar {
  &__img {
    border-radius: 50%;
  }
}
</style>