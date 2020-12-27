<template>
  <main>
    <Navbar />
    <Hero />
    <!-- <Footer /> -->
  </main>
</template>
<script>
import Navbar from "~/components/navbar.vue";
import Hero from "~/components/hero.vue";
// import Footer from "~/components/footer.vue";

export default {
  components: {
    Navbar,
    Hero,
    // Footer,
  },
};
</script>

