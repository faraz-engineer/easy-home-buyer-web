<script setup>
import {ref} from 'vue';

const isOpen1 = ref(false);
const isOpen2 = ref(false);
const isOpen3 = ref(false);
const isOpen4 = ref(false);
const isOpen5 = ref(false);
const isOpen6 = ref(false);
const isOpen7 = ref(false);
const isOpen8 = ref(false);
const isOpen9 = ref(false);
const isOpen10 = ref(false);


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
                        <a class="faq-question-link" @click="isOpen1 = !isOpen1">
                            <img v-if="!isOpen1" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I sell a house in probate?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen1" class="buy-house-spokane-paragraph faq-paragraph">
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
                        <a class="faq-question-link" @click="isOpen2 = !isOpen2">
                            <img v-if="!isOpen2" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can you stop a foreclosure?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen2" class="buy-house-spokane-paragraph">
                                Can we ever. We have stopped dozens of foreclosures and work hand in hand with the best
                                closing attorneys in town to get auctions delayed if necessary. We have had people call
                                us the day before an auction and we were able to help. I highly recommend not waiting
                                that long but we have helped dozens of sellers avoid foreclosure.
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="isOpen3 = !isOpen3">
                            <img v-if="!isOpen3" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Do you buy properties in any condition?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen3" class="buy-house-spokane-paragraph">
                                Absolutely. Every month we buy homes that need absolutely no work, and homes that should
                                be featured on some house flipping show on HGTV. We’ve torn down houses to build new,
                                and bought large estates. There really isn’t a home we won’t consider as long as we get
                                to help a seller and it’s a win-win.
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="isOpen4 = !isOpen4">
                            <img v-if="!isOpen4" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Why should I choose The Easy Home Buyer?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen4" class="buy-house-spokane-paragraph">
                                We do business differently. To be totally honest, cash home buyers can garner a bad
                                reputation because it’s prevalent for them to “back out” or “price drop” people. We are
                                the highest rated and reviewed company in our area because we have successfully closed
                                99% of all contracts we have ever entered into. Not to get on a soap box but if we tell
                                somebody we are going to buy their house we just plain do. We understand people are
                                planning their next life chapter and often have already set that ball in motion when we
                                sign a contract. At our company, we are men and women of our word. But please, don’t
                                take our word for it. Read over 100 five star reviews on google where other sellers have
                                talked about their experience. Or give us a call and talk to us, at the end of the day
                                we are here to help you.
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="isOpen5 = !isOpen5">
                            <img v-if="!isOpen5" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            How does a cash offer sale work?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen5" class="buy-house-spokane-paragraph">
                                Because we don’t use banks it’s extremely quick and easy. The short version is we agree
                                on a price that works for both of us, and the terms (like how long you want to close, do
                                you want to leave everything in the house etc). We then submit your purchase agreement
                                to our closing and title companies, there will be some limited documents and questions
                                they need answered (all of which we handle for you, like loan payoffs). Then we just
                                wait until the close date. There are no appraisals, no commissions. It’s honestly as
                                quick and easy as you can sell a house. Our average seller we get to work with typically
                                has less than 1 hour into the home selling process and collects their cash within 1-3
                                weeks.
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="isOpen6 = !isOpen6">
                            <img v-if="!isOpen6" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Do you buy houses with tenants?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen6" class="buy-house-spokane-paragraph faq-paragraph">
                                Only dozens of times per year. We understand that selling a house with tenants can be
                                very delicate situations. We ALWAYS work with tenants to see what the best plan for them
                                is. We’ve bought a lot of homes with tenants, some prefer to stay in place. Other houses
                                we have purchased the tenants prefer to move on and have the place fixed up. We walk all
                                parties through their options and see exactly how we can help.
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="isOpen7 = !isOpen7">
                            <img v-if="!isOpen7" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Can I live in the house after closing?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen7" class="buy-house-spokane-paragraph">
                                We’d love to talk to you about this. We allow people to live in the home post-closing
                                often. We can walk you through what those options are. We completely understand you
                                might need the cash now, but a month or two to find another place to live or plan the
                                next chapter of your life. We’re here to help you with that.
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="isOpen8 = !isOpen8">
                            <img v-if="!isOpen8" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            How quickly can you close?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen8" class="buy-house-spokane-paragraph">
                                Because we pay cash, it’s really on your timeline. We’ve closed houses in as little as 3
                                days, and we’ve extended closings out for months at the request of the seller so they
                                could make time to find another place. We often will let people live in the house after
                                closing if that can help your situation too.
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="isOpen9 = !isOpen9">
                            <img v-if="!isOpen9" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Do you buy any type of property?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen9" class="buy-house-spokane-paragraph">
                                Yes indeed. We have bought everything from bare land, to tear down houses, condos,
                                apartment buildings, mansions, houses that needed zero work and houses that need full
                                rehabs. We love every scenario as long as we get to help the person selling.
                            </p>
                        </transition>
                    </div>
                    <div class="faq-question-point">
                        <a class="faq-question-link" @click="isOpen10 = !isOpen10">
                            <img v-if="!isOpen10" width="25px" src="~/assets/images/plus-large-svgrepo-com.svg">
                            <img v-else class="minus-icon" width="25px" src="~/assets/images/minus-svgrepo-com.svg">
                            Do I need to have my house empty to sell?
                        </a>
                        <transition name="faq-slide">
                            <p v-if="isOpen10" class="buy-house-spokane-paragraph">
                                Absolutely not ????. We buy houses in any condition, regardless of content. We have a
                                “leave behind” special that we would love to talk with you about. Many sellers decide to
                                sell to us and prefer to have us take on all of the items left behind. We’re REALLY good
                                at cleaning out properties (practice makes perfect!)
                            </p>
                        </transition>
                    </div>
                </div>
                <div class="choose-easy-home-buyer-box faq-easy-home-buyer-box">
                    <div class="choose-easy-home-buyer-wrapper">
                        <div class="sell-my-house-reviews-image">
                            <img class="img-fluid" src="~assets/images/google-review-cash-home-buyer-5.webp">
                            <img class="img-fluid"
                                 src="~assets/images/testimonials-best-sell-my-house-fast-company.webp">
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