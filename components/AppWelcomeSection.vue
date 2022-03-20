<template>
    <div>
        <div class="welcome-area" id="welcome">
            <div class="header-text">
                <div class="container">
                    <div class="row">
                        <div class="offset-xl-3 col-xl-6 offset-lg-2 col-lg-8 col-md-12 col-sm-12">
                            <h1>We provide the best <strong>cleaning service</strong> to your house, apartment and more!</h1>
                            <a href="#features" class="main-button-slider">Book Your Cleaning Service!</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <section class="section home-feature">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <div class="row">
                            <WelcomeCard />
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
import WelcomeCard from './WelcomeCard.vue'

export default {
    components: { WelcomeCard }
}
</script>