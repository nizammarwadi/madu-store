<template>
  <div>
    <NavbarSection/>
    <Intro/>
    <AboutSection/>
    <ProdukSection/>
    <BenefitSection/>
    <Flow/>
    <TestimoniSection/>
    <Footer/>
  </div>
</template>
<script>
import NavbarSection from "~/components/atoms/NavbarSection.vue"
import Intro from "~/components/atoms/Intro.vue"
import AboutSection from "~/components/atoms/AboutSection.vue"
import ProdukSection from "~/components/atoms/ProdukSection.vue"
import BenefitSection from "~/components/atoms/BenefitSection.vue"
import Flow from "~/components/atoms/Flow.vue"
import TestimoniSection from "~/components/atoms/TestimoniSection.vue"
import Footer from "~/components/atoms/Footer.vue"
export default {
  components: {
    NavbarSection: NavbarSection,
    Intro: Intro,
    AboutSection: AboutSection,
    ProdukSection: ProdukSection,
    BenefitSection: BenefitSection,
    Flow: Flow,
    TestimoniSection: TestimoniSection,
    Footer: Footer,
  }
}
</script>


<style>

</style>