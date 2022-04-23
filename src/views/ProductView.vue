<template>
  <div class="product">
    <HeaderShop/>
    <p>
      Hallo wellcome to fitri cantik
    </p>
    <FooterShop/>

  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShop from '@/components/HeaderShop.vue'
import FooterShop from '@/components/FooterShop.vue'

export default {
  name: 'ProductView',
  components: {
    HeaderShop,
    FooterShop
  }
};
</script>

