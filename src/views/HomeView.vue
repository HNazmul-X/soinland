<template>
    <div class="homepage-main">
        <div class="background img-container">
            <img src="@/assets/images/homepage-banner.png" alt="" />
        </div>
        <div class="homepage-main-container d-container">
            <div class="top-corner-button text-right py-5">
                <button class="primary-btn font-mulish text-uppercase px-10 py-4 shadow radius">Private Presale is live</button>
            </div>
            <header class="home-page-header">
                <div class="header-flex">
                    <div class="logo">
                        <img src="@/assets/images/soinland-full-white-logo.png" alt="" />
                    </div>
                    <div class="title">
                        <h3>DECENTRALIZED GEODATA FOR</h3>
                        <h1>Multiverse</h1>
                    </div>
                    <div class="bottom-line">
                        <h5 class="d-flex align-center">
                            DECENTRALIZED GEODATA FOR
                            <svg width="15" height="18" viewBox="0 0 15 18" class="ml-3" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M0.5 1.20577L14 9L0.499999 16.7942L0.5 1.20577Z" stroke="#7C00C6" />
                            </svg>
                        </h5>
                    </div>
                </div>
            </header>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: "HomeVue",
});
</script>

<style scoped lang="scss">
@use "../styles/views/homeView";
</style>
