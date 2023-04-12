<script>
import bannerTitle from './components/AppBanner.vue';
export default {
  components: {
    bannerTitle
  },
  data() {
    return {
      title: 'Hello Vite'
    }
  }
}
</script>

<template>
  <h1 class="main-title">{{ title }}</h1>
  <bannerTitle />
</template>

<style>
.main-title {
  color: red;
}
</style>
