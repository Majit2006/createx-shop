<template>
  <div>
    <topbar />
    <Navbar />
    <nuxt />
  </div>
</template>
<script>
import topbar from "~/components/topbar/topbar.vue";
import Navbar from "~/components/navbar/navbar.vue";
export default {
  components: {
    topbar,
    Navbar,
  },
};
</script>
