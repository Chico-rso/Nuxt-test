<template>
  <div>
    <Navbar />
    <main>
      <div class="container">
        <nuxt />
      </div>
    </main>
  </div>
</template>

<script>
import Index from "@/pages/index.vue";
import Navbar from "@/components/Navbar.vue";
import About from "@/pages/about.vue";
export default {
  components: {
    Index,
    Navbar,
    About,
  },
};
</script>

<style lang="scss" scoped>
</style>