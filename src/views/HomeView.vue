<template>
  <div class="home">
    <HeaderShop/>
    <HeroShop/>
    <WomenShop/>
    <InstaShop/>
    <PartnerShop/>

  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShop from '@/components/HeaderShop.vue'
import HeroShop from '@/components/HeroShop.vue'
import WomenShop from '@/components/WomenShop.vue'
import InstaShop from '@/components/InstaShop.vue'
import PartnerShop from '@/components/PartnerShop.vue'

export default {
  name: 'HomeView',
  components: {
    HeaderShop,
    HeroShop,
    WomenShop,
    InstaShop,
    PartnerShop
  }
};
</script>


