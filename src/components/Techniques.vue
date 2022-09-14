<template>
    <div>
        <b-row>
            <b-col class="text-default">
                Minhas principais habilidades
            </b-col>
        </b-row>
        <br>
        <b-row class="text-center">
            <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <img src="/img/logos/Vue.js_Logo_2.svg" alt="Vue" v-b-popover.hover.top="'Vue'">
                </div>
            </div>
            <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <img src="/img/logos/javascript-logo.svg" alt="Java Script" v-b-popover.hover.top="'Java Script'">
                </div>
            </div>
            <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <img src="/img/logos/html-1.svg" alt="HTML" v-b-popover.hover.top="'HTML'">
                </div>
            </div>
            <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <img src="/img/logos/css-3.svg" alt="CSS" v-b-popover.hover.top="'CSS'">
                </div>
            </div>
            <!-- <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <b-img rounded src="/img/logos/nodejs-1.svg" alt="Node.js" class="bg-light p-1" v-b-popover.hover.top="'Node.js'"/>
                </div>
            </div> -->
            <!-- <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <img src="/img/logos/React-icon.svg" alt="React" v-b-popover.hover.top="'React'">
                </div>
            </div> -->
            <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <img src="/img/logos/bootstrap-4.svg" alt="Bootstrap" v-b-popover.hover.top="'Bootstrap'">
                </div>
            </div>
            <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <img src="/img/logos/sass-1.svg" alt="Sass" v-b-popover.hover.top="'Sass'">
                </div>
            </div>
            <!-- <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <img src="/img/logos/ruby.svg" alt="Ruby" v-b-popover.hover.top="'Ruby on Rails'">
                </div>
            </div> -->
            <div class="hability">
                <div class="animated fadeInUp" style="animation-duration: 1s; opacity: 1; cursor:pointer;">
                    <b-img rounded src="/img/logos/cypress.svg" alt="Cypress" class="bg-light p-1" v-b-popover.hover.top="'Cypress'"/>
                </div>
            </div>
        </b-row>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .hability{
        margin-top: 50px !important;
        width: 25% !important;
        img{
            height: 50px;
        }
    }
</style>