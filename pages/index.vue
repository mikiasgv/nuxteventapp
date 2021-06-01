<template>
    <div class="container">
        <main class="container">
            <AppHeader />
            <AppRestaurantInfo />
        </main>
    </div>
</template>

<script>
import AppHeader from "@/components/AppHeader";
import AppRestaurantInfo from "@/components/AppRestaurantinfo";
export default {
    components: {
        AppHeader,
        AppRestaurantInfo,
    },
};
</script>

<style>
</style>
