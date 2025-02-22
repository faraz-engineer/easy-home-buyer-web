<script setup>
import {ref} from 'vue';

const isOpen = ref(false);

const toggleVisibility = () => {
    isOpen.value = !isOpen.value;
};


</script>


<template>
    <section class="faq-section blog-section">
        <div class="container-fluid">
            <div class="blog-heading">
                <h1 class="fw-bolder text-white">Frequently Asked Questions</h1>
                <p class="blog-paragraph">
                    FAQ
                </p>
            </div>
        </div>
    </section>
    <section class="faq-question-section">
        <div class="container-fluid">
            <div class="faq-question-wrapper">
                <div class="faq-question">
                    <div class="have-some-question">
                        <h1 class="have-some-question-heading">Do you have some questions?</h1>
                        <p class="buy-house-spokane-paragraph pt-4 pb-4">That’s quite normal. We’ve compiled a list of
                            the most
                            common questions people ask us and their answers. If you still have an additional question,
                            you can contact us or give us a call and we’ll be glad to help.
                        </p>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="toggleVisibility">
                            <img v-if="!isOpen" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen" class="buy-house-spokane-paragraph faq-paragraph">
                                Yes you can. We buy dozens of homes every year in the probate process, or help prior to
                                the
                                probate process. Many sellers don’t know that you can actually forego the probate
                                process if
                                the necessary paperwork is filled out (our closing attorney does all of this for us,
                                free of
                                charge to our sellers). We buy inherited properties after the probate process and
                                anywhere
                                in-between. We have become known as probate experts in our area because of our ability
                                to
                                help people navigate the process so well. Even if you just have questions about the
                                probate
                                process, please give us a call!
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="toggleVisibility">
                            <img v-if="!isOpen" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen" class="buy-house-spokane-paragraph">
                                Yes you can. We buy dozens of homes every year in the probate process, or help prior to
                                the
                                probate process. Many sellers don’t know that you can actually forego the probate
                                process if
                                the necessary paperwork is filled out (our closing attorney does all of this for us,
                                free of
                                charge to our sellers). We buy inherited properties after the probate process and
                                anywhere
                                in-between. We have become known as probate experts in our area because of our ability
                                to
                                help people navigate the process so well. Even if you just have questions about the
                                probate
                                process, please give us a call!
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="toggleVisibility">
                            <img v-if="!isOpen" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen" class="buy-house-spokane-paragraph">
                                Yes you can. We buy dozens of homes every year in the probate process, or help prior to
                                the
                                probate process. Many sellers don’t know that you can actually forego the probate
                                process if
                                the necessary paperwork is filled out (our closing attorney does all of this for us,
                                free of
                                charge to our sellers). We buy inherited properties after the probate process and
                                anywhere
                                in-between. We have become known as probate experts in our area because of our ability
                                to
                                help people navigate the process so well. Even if you just have questions about the
                                probate
                                process, please give us a call!
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="toggleVisibility">
                            <img v-if="!isOpen" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen" class="buy-house-spokane-paragraph">
                                Yes you can. We buy dozens of homes every year in the probate process, or help prior to
                                the
                                probate process. Many sellers don’t know that you can actually forego the probate
                                process if
                                the necessary paperwork is filled out (our closing attorney does all of this for us,
                                free of
                                charge to our sellers). We buy inherited properties after the probate process and
                                anywhere
                                in-between. We have become known as probate experts in our area because of our ability
                                to
                                help people navigate the process so well. Even if you just have questions about the
                                probate
                                process, please give us a call!
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="toggleVisibility">
                            <img v-if="!isOpen" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen" class="buy-house-spokane-paragraph">
                                Yes you can. We buy dozens of homes every year in the probate process, or help prior to
                                the
                                probate process. Many sellers don’t know that you can actually forego the probate
                                process if
                                the necessary paperwork is filled out (our closing attorney does all of this for us,
                                free of
                                charge to our sellers). We buy inherited properties after the probate process and
                                anywhere
                                in-between. We have become known as probate experts in our area because of our ability
                                to
                                help people navigate the process so well. Even if you just have questions about the
                                probate
                                process, please give us a call!
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="toggleVisibility">
                            <img v-if="!isOpen" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen" class="buy-house-spokane-paragraph faq-paragraph">
                                Yes you can. We buy dozens of homes every year in the probate process, or help prior to
                                the
                                probate process. Many sellers don’t know that you can actually forego the probate
                                process if
                                the necessary paperwork is filled out (our closing attorney does all of this for us,
                                free of
                                charge to our sellers). We buy inherited properties after the probate process and
                                anywhere
                                in-between. We have become known as probate experts in our area because of our ability
                                to
                                help people navigate the process so well. Even if you just have questions about the
                                probate
                                process, please give us a call!
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="toggleVisibility">
                            <img v-if="!isOpen" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen" class="buy-house-spokane-paragraph">
                                Yes you can. We buy dozens of homes every year in the probate process, or help prior to
                                the
                                probate process. Many sellers don’t know that you can actually forego the probate
                                process if
                                the necessary paperwork is filled out (our closing attorney does all of this for us,
                                free of
                                charge to our sellers). We buy inherited properties after the probate process and
                                anywhere
                                in-between. We have become known as probate experts in our area because of our ability
                                to
                                help people navigate the process so well. Even if you just have questions about the
                                probate
                                process, please give us a call!
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="toggleVisibility">
                            <img v-if="!isOpen" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen" class="buy-house-spokane-paragraph">
                                Yes you can. We buy dozens of homes every year in the probate process, or help prior to
                                the
                                probate process. Many sellers don’t know that you can actually forego the probate
                                process if
                                the necessary paperwork is filled out (our closing attorney does all of this for us,
                                free of
                                charge to our sellers). We buy inherited properties after the probate process and
                                anywhere
                                in-between. We have become known as probate experts in our area because of our ability
                                to
                                help people navigate the process so well. Even if you just have questions about the
                                probate
                                process, please give us a call!
                            </p>
                        </transition>
                    </div>
                </div>
                <div class="choose-easy-home-buyer-box">
                    <div class="choose-easy-home-buyer-wrapper">
                        <div class="sell-my-house-reviews-image">
                            <img class="img-fluid" src="~assets/images/google-review-cash-home-buyer-5.webp">
                            <img class="img-fluid" src="~assets/images/testimonials-best-sell-my-house-fast-company.webp">
                        </div>
                        <div class="choose-easy-home-buyer">
                            <h1 class="choose-easy-home-buyer-heading">
                                Why Choose The Easy Home Buyer?
                            </h1>
                        </div>
                        <div class="areas-we-serve-points faq-points">
                            <img width="30px" src="~/assets/images/check-big-svgrepo-com.svg">
                            <p class="areas-we-serve-points-paragraph">Zero Fees to Sell Your House</p>
                        </div>
                        <div class="areas-we-serve-points faq-points">
                            <img width="30px" src="~/assets/images/check-big-svgrepo-com.svg">
                            <p class="areas-we-serve-points-paragraph">Highest Off-Market Price</p>
                        </div>
                        <div class="areas-we-serve-points faq-points">
                            <img width="30px" src="~/assets/images/check-big-svgrepo-com.svg">
                            <p class="areas-we-serve-points-paragraph ">Sell As-Is. No Cleanup. No Repairs.</p>
                        </div>
                        <div class="areas-we-serve-points faq-points">
                            <img width="30px" src="~/assets/images/check-big-svgrepo-com.svg">
                            <p class="areas-we-serve-points-paragraph">Close In As Little As 7 Days</p>
                        </div>
                        <div class="areas-we-serve-points faq-points">
                            <img width="30px" src="~/assets/images/check-big-svgrepo-com.svg">
                            <p class="areas-we-serve-points-paragraph">No Closing Costs</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="washington-property-address-section">
        <div class="container-fluid">
            <div class="how-we-sell-house-fast-wrapper the-easy-way-to-sell-house-wrapper">
                <h1 class="common-heading how-we-sell-house-fast-heading" style="color: black">
                    ENTER THE WASHINGTON PROPERTY ADDRESS BELOW
                </h1>
                <p class="how-we-sell-house-fast-paragraph">
                    TO GET YOUR FREE CASH OFFER
                </p>
            </div>
            <div class="washington-property-address-wrapper">
                <form>
                    <div class="washington-property-address-input">
                        <input class="property-form-input" type="text" placeholder="Property Address *">
                    </div>
                    <div class="washington-property-address-input">
                        <input class="property-form-input" type="text" placeholder="Name *">
                    </div>
                    <div class="washington-property-address-input">
                        <input class="property-form-input" type="text" placeholder="Email *">
                    </div>
                    <div class="washington-property-address-input">
                        <input class="property-form-input" type="tel" placeholder="Phone *">
                    </div>
                    <div class="sell-my-house-fast-spokane-btn">
                        <button class="free-offer-header-btn">
                            GET YOUR CASH OFFER
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>
    <section class="sell-your-house-with-stress-free-section bg-white">
        <div class="container-fluid">
            <div class="sell-my-house-fast-spokane-wrapper">
                <div class="sell-my-house-fast-spokane-description">
                    <h1 class="sell-my-house-fast-spokane-heading faq-sell-my-house-fast">Still have some more
                        questions?</h1>
                    <p class="sell-my-house-fast-spokane-paragraph faq-sell-my-house-fast-paragraph">As a homeowner,
                        selling an unwanted property can be a daunting task. That’s why many homeowners turn to real
                        estate investors who offer cash for homes. If you’re considering this option, it’s important to
                        do your research and find a reputable company that can help you get the best possible price for
                        your property.
                    </p>
                    <p class="sell-my-house-fast-spokane-paragraph faq-sell-my-house-fast-paragraph">
                        We specialize in helping homeowners sell unwanted properties for cash. Whether you’re dealing
                        with a foreclosure, inherited property, or simply need to
                        <a href="#" class="buy-house-spokane-link faq-link">
                            sell my house fast Spokane
                        </a>
                        , we can help. Our team of experienced professionals can provide a no-hassle situation
                        evaluation to help
                        you understand your options and make an informed decision.
                    </p>
                    <p class="sell-my-house-fast-spokane-paragraph faq-sell-my-house-fast-paragraph">
                        If you have any questions or would like to schedule a consultation with our team, please don’t
                        hesitate to contact us. We’re here to help you navigate the complex world of real estate
                        investing and ensure that you get the best possible outcome for your situation.
                    </p>
                </div>
                <div class="house-buyer-team-image">
                    <img class="img-fluid" src="~assets/images/the-easy-home-buyer-team.jpg">
                </div>
            </div>
        </div>
    </section>


</template>


<style scoped>

</style>