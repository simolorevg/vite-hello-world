<script>
export default {
    data() {
        return {
            bannerTitle: 'This is AppBanner'
        }
    }
}
</script>
<template>
    <div class="banner">
        <h2 class="banner-title">{{ bannerTitle }}</h2>
    </div>
</template>
<style>
.banner {
    width: 100%;
    border: 1px solid white;
}

.banner-title {
    text-align: center;
}
</style>