<template>
  <v-app>
  <v-main>
  <Banner />
  <Features id="features" />
  <Footer />
  </v-main>
  
  </v-app>
</template>

<script>
// @ is an alias to /src
import Banner from '@/components/Banner.vue'
import Features from '@/components/Features'
import Footer from '@/components/Footer'

export default {
  name: 'Home',
  components: {
    Banner,
    Features,
    Footer
  }
}
</script>
