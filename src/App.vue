<template>
  <!-- header -->
  <header>
    <!-- title -->
    <AppTitle />
    <!-- jumbo -->
    <AppHero />
  </header>
</template>

<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue"
export default {
  // name root app
  name: "App",
  // components that uses
  components: {
    AppTitle,
    AppHero
  },
  // classic vue
  data() {
  },
  methods: {

  },
  computed: {

  },
  mounted() {

  }
}
</script>

<style lang="css"></style>