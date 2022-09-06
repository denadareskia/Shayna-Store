<template>
  <div class="home">
    <HeaderComponent/>
    <HeroComponent />
    <ProductCarousel />
    <InstaComponent />
    <PartnerComponent />
    <FooterComponent />
    
  </div>
</template>

<script>
// @ is an alias to /src
 import HeaderComponent from '@/components/HeaderComponent.vue'
 import HeroComponent from '@/components/HeroComponent.vue'
 import ProductCarousel from '@/components/ProductCarousel.vue'
 import InstaComponent from '@/components/InstaComponent.vue'
 import PartnerComponent from '@/components/PartnerComponent.vue'
 import FooterComponent from '@/components/FooterComponent.vue'

export default {
  name: "HomeView",
  components: {
    HeaderComponent,
    HeroComponent,
    ProductCarousel,
    InstaComponent,
    PartnerComponent,
    FooterComponent
  },
};
</script>
