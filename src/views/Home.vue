<template>
  <div class="home">
    <HeaderHaneeda/>
    <HeroHaneeda/>
    <WomenHaneeda/>
    <InstaHaneeda/>
    <PartnerHaneeda/>
    <FooterHaneeda/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderHaneeda from '@/components/HeaderHaneeda.vue';
import HeroHaneeda from '@/components/HeroHaneeda.vue';
import WomenHaneeda from '@/components/WomenHaneeda.vue';
import InstaHaneeda from '@/components/InstaHaneeda.vue';
import PartnerHaneeda from '@/components/PartnerHaneeda.vue';
import FooterHaneeda from '@/components/FooterHaneeda.vue';

export default {
  name: 'Home',
  components: {
  HeaderHaneeda,
  HeroHaneeda,
  WomenHaneeda,
  InstaHaneeda,
  PartnerHaneeda,
  FooterHaneeda
  
  }
}
</script>
