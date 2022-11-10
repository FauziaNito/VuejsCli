<template>
    <div>
        <NavbarSection/>
        <HeaderSection/>
        <BodySection/>
        <FooterSection/>

    </div>
</template>

<script>
import NavbarSection from "./NavbarSection.vue"
import HeaderSection from "./HeaderSection.vue"
import BodySection from "./BodySection.vue"
import FooterSection from "./FooterSection.vue"
export default {
    
    name: "MainLayout",
    components:{
        HeaderSection,
        BodySection,
        FooterSection,
        NavbarSection
    },
    data(){return{
        food: "Matooke"
    }},
    methods:{}
}

</script>

<style>

</style>