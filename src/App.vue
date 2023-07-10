<template>
  <nav-component/>

  <router-view/>

  <footer-component/>
</template>


<script>

import NavComponent from "./components/layouts/NavComponent.vue";
import FooterComponent from "./components/layouts/FooterComponent.vue";
export default {
  components: { FooterComponent , NavComponent },
}
</script>
