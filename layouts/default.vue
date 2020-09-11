<template>
  <div>
      <GKHeader/>
     
    <Nuxt />

     <GKFooter/>
  </div>
</template>

<script>


import GKHeader from '~/components/Client/Navigation/GKHeader'
import GKFooter from '~/components/Client/Navigation/GKFooter'
export default {
  

    components:{
      GKHeader,GKFooter
    }


}


</script>
