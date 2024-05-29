<script>
import AppHero from "./components/AppHero.vue";

export default {
  name: "MyApp",
  data() {
    return {
      title: "La mia prima app con Vite!",
    };
  },

  components: {
    AppHero,
  },
};
</script>

<template>
  <h1>{{ title }}</h1>
  <AppHero />
</template>

<style>
h1 {
  color: green;
}
</style>
