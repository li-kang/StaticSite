<template>
  <div>
    <Navigate />
    <Banner />
    <Products />
    <SuccessCase />
    <Footer />
  </div>
</template>

<script>
import Navigate from '~/components/Navigate.vue'
import Banner from '~/components/Banner.vue'
import SuccessCase from '~/components/SuccessCase.vue'
import Products from '~/components/Products.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Navigate, Banner, SuccessCase, Products, Footer
  }
}
</script>

<style>

</style>
