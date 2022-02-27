<template>
  <div class="home">
    <Header />
    <Hero />
    <WomenHero />
    <Instagram />
    <Partner />
    <Footer />


  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import WomenHero from '@/components/WomenHero.vue';
import Instagram from '@/components/Instagram.vue';
import Partner from '@/components/Partner.vue';
import Footer from '@/components/Footer.vue';


export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    WomenHero,
    Instagram,
    Partner,
    Footer
  }
}
</script>
