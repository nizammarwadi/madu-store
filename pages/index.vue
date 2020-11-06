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
import NavbarSection from "~/components/organisms/NavbarSection.vue"
import Intro from "~/components/organisms/Intro.vue"
import AboutSection from "~/components/organisms/AboutSection.vue"
import ProdukSection from "~/components/organisms/ProdukSection.vue"
import BenefitSection from "~/components/organisms/BenefitSection.vue"
import Flow from "~/components/organisms/Flow.vue"
import TestimoniSection from "~/components/organisms/TestimoniSection.vue"
import Footer from "~/components/organisms/Footer.vue"
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