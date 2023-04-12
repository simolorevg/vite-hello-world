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
  <h1>{{ title }}</h1>
  <bannerTitle />
</template>

<style></style>
