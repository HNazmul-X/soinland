<script setup lang="ts">
import { RouterLink } from "vue-router";
import HelloWorld from "../components/HelloWorld.vue";
import globeIcon from "../assets/images/globe.png";
import { ref } from "vue";

let icons = ref([...new Array(5)]);
</script>

<template>
    <div class="dashboard-wrapper">
        <aside>
            <div class="logo">
                <img src="@/assets/images/logo.png" alt="" />
            </div>
            <v-row class="flex-column sidebar-items py-10" align="center">
                <v-col v-for="icon in icons" class="pa-0">
                    <div class="items text-center sidebar-item">
                        <img src="@/assets/images/globe.png" alt="" />
                    </div>
                </v-col>
            </v-row>
        </aside>
        <div class="content">
            <div class="content-container">
                <slot />
            </div>
        </div>
    </div>
</template>

<style></style>
