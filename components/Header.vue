<script setup>

import {ref} from 'vue';
const isMenuOpen = ref(false);

const toggleMenu = () => {
    isMenuOpen.value = !isMenuOpen.value;
};


</script>

<template>
    <header>
        <div class="header-wrapper">
            <h3 class="common-heading">Spokane & CDA’s Most Trusted Home Buyer</h3>
            <h3 class="common-heading">Call Us at (509) 530-2088</h3>
        </div>
        <div class="header-container">
            <div class="header-logo">
                <a href="/"><img class="img-fluid" src="~assets/images/the-easy-home-buyer-logo.webp"></a>
            </div>
            <div class="navbar-links">
                <ul class="navbar" :class="{ 'show-menu': isMenuOpen }">
                    <li><a class="navbar-user-link" href="/about-us">About Us</a></li>
                    <li><a class="navbar-user-link" href="/faq">FAQ</a></li>
                    <li><a class="navbar-user-link" href="/contact-us">Contact</a></li>
                </ul>
            </div>
            <div class="header-btn">
                <button class="free-offer-header-btn">
                    GET MY FREE OFFER
                </button>
            </div>
            <div class="hamburger"   @click="toggleMenu">
                <img v-if="!isMenuOpen" width="32px" src="~/assets/images/hamburger-svgrepo-com.svg">
                <img  v-else width="50px" src="~/assets/images/cross.svg">
            </div>
        </div>
    </header>
</template>

<style scoped></style>
