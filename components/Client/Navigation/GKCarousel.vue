<template>
<div class="mobile:max-h-40" style="height:600px; width:100%;">   <swiper   ref="mySwiper" :options="swiperOptions">
    <swiper-slide > <img style="height:600px; width:100%;"  src="~/assets/GK.jpg"/>  </swiper-slide>
    <swiper-slide><img  style="height:600px; width:100%;" src="~/assets/GK.jpg"/></swiper-slide>
    <swiper-slide><img style="height:600px; width:100%;"  src="~/assets/GK.jpg"/></swiper-slide>
    <swiper-slide><img style="height:600px; width:100%;"  src="~/assets/GK.jpg"/></swiper-slide>
    <swiper-slide><img style="height:600px; width:100%;"  src="~/assets/GK.jpg"/></swiper-slide>
    <div class="swiper-pagination" slot="pagination"></div>
  </swiper>
  </div>
</template>

<script>
  export default {
    name: 'carrousel',
    data() {
      return {
        swiperOptions: {
          cubeEffect: {
    slideShadows: true,
  },

        slidesPerView: 1,

        autoplay: {
          delay: 5000
        },
          pagination: {
            el: '.swiper-pagination',
            clickable: true
          },
          // Some Swiper option/callback...
        }
      }
    },

  }
</script>

