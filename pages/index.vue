<template>
    <div class="col-12">
        <AppNavbar />
        <AppWelcomeSection />
        <AboutUsSection />
    </div>
</template>

<script>
import AboutUsSection from "../components/AppAboutUsSection.vue";
import AppNavbar from "../components/AppNavbar.vue";
import AppWelcomeSection from "../components/AppWelcomeSection.vue";

export default {
    components: { AboutUsSection, AppNavbar, AppWelcomeSection }
}
</script>
