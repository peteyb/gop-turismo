<template>
  <Html lang="en-gb">
    <div class="centered">
      <a
        href="https://1drv.ms/x/s!AlxI-aPw3gA9gagKvHJW0ZRW3O0_YA?e=fL4wgx"
        target="_blank"
        rel="noopener"
        class="link"
        >Gamers on PlayStation</a
      >
    </div>
  </Html>
</template>

<script setup>
useHead({
  title: "Gamers on PlayStation",
  viewport: "width=device-width, initial-scale=1, maximum-scale=1",
  charset: "utf-8",
  meta: [{ name: "description", content: "GoP landing page" }],
});
</script>

<style>
@font-face {
  font-family: "Helvetica Neue 97";
  src: url("~/assets/fonts/helvetica_neue_97_black_condensed-webfont.woff2") format("woff2"),
    url("~/assets/fonts/helvetica_neue_97_black_condensed-webfont.woff") format("woff");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

:root {
  --font-family: "Helvetica Neue 97", -apple-system, BlinkMacSystemFont, Arial, sans-serif;
}

html {
  background: url(~/assets/images/background.jpg) no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

.centered {
  position: fixed;
  top: 80%;
  left: 50%;
  transform: translate(-50%, -80%);
}

.link {
  font-family: var(--font-family);
  font-size: 5rem;
  color: cornsilk;
}
</style>
