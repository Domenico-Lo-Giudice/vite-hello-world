<script>
// import componente
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

//definizione componente
export default {
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <AppTitle />
  <AppHero />
</template>

<style scoped></style>
