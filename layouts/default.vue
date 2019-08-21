<template>
  <div>
    <main-navbar></main-navbar>
    <nuxt />
  </div>
</template>

<script>
import mainNavbar from '~components/main-navbar.vue'
export default {
  components: {
    mainNavbar
  }
}
</script>
