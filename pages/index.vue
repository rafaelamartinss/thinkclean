<template>
    <div class="col-12">
        <AppNavbar />
        <AppWelcomeSection />
        <AppCard />
    </div>
</template>

<script>
import AppCard from "../components/AppCard.vue";
import AppNavbar from "../components/AppNavbar.vue";
import AppWelcomeSection from "../components/AppWelcomeSection.vue";

export default {
    components: { AppCard, AppNavbar, AppWelcomeSection }
}
</script>
