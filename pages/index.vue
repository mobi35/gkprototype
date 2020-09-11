<template>
  <div >
    <GKCarousel/>
    <BestSeller/>
      <Gallery/>
        <Instagram/>
  </div>
</template>

<script>
import GKCarousel from '~/components/Client/Navigation/GKCarousel'
import BestSeller from '~/components/Client/Product/ProductSlider'
import Gallery from '~/components/Client/Social/Gallery'
import Instagram from '~/components/Client/Social/Instagram'
export default {
  components:{
    GKCarousel,BestSeller,Gallery,Instagram
  }
}
</script>


