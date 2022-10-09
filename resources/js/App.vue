<template>
  <Navbar />
  <main class="min-h-screen">
    <Additem />
    <Listitem />
  </main>
  <Footer />
</template>
<script setup>
import Navbar from "./components/Navbar.vue";
import Additem from "./components/Additem.vue";
import Listitem from "./components/Listitem.vue";
import Footer from "./components/Footer.vue";
// export default {};
</script>

<style></style>
