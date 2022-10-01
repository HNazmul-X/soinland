<script lang="ts" setup>
import { RouterView } from "vue-router";
import Dashboard from "./Layout/Dashboard.vue";
</script>
<template>
    <v-app>
        <v-main>
            <Dashboard>
                <RouterView />
            </Dashboard>
        </v-main>
    </v-app>
</template>


<style>
 
</style>