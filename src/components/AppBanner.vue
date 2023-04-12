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
        <img class="banner-img" src="../assets/roma.jpg" alt="Roma">
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

.banner-img {
    width: 100%;
    height: 400px;
    object-fit: cover;
}
</style>