<template>
  <div class="home">
    <Header />
    <Hero />
    <Barang />
    <Insta />
    <Partner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import Barang from '@/components/Barang.vue'
import Insta from '@/components/Insta.vue'
import Partner from '@/components/Partner.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'Home',
  components: {
Header,
Hero,
Barang, 
Insta,
Partner,
Footer
  }
}
</script>
