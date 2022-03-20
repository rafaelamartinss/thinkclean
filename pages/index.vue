<template>
    <div class="col-12">
        <AppNavbar />
        <AppCard />
    </div>
</template>

<script>
import AppCard from "../components/AppCard.vue";
import AppNavbar from "../components/AppNavbar.vue";

export default {
    components: { AppCard, AppNavbar }
}
</script>
