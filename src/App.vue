<template>
  <div id="app" class="d-flex flex-column">
    <NavBar />
    <div class="container py-2 flex-grow-1">
      <routerView />
    </div>
    <Footer />
  </div>
</template>

<script>
import NavBar from "@/components/Layouts/NavBar.vue";
import Footer from "@/components/Layouts/Footer.vue";

export default {
  components: {
    NavBar,
    Footer,
  },
};
</script>
