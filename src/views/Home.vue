<template>
  <div class="home">
    <HeaderSevenstore />
    <HeroSevenstore />
    <WomanSevenstore />
    <InstaSevenstore />
    <PartnerSevenstore />
    <FooterSevenstore/>
  
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderSevenstore from "@/components/HeaderSevenstore.vue";
import HeroSevenstore from "@/components/HeroSevenstore.vue";
import WomanSevenstore from "@/components/WomanSevenstore.vue";
import InstaSevenstore from "@/components/InstaSevenstore.vue";
import PartnerSevenstore from "@/components/PartnerSevenstore.vue";
import FooterSevenstore from "@/components/FooterSevenstore.vue";


export default {
  name: "home",
  components: {
    HeaderSevenstore,
    HeroSevenstore,
    WomanSevenstore,
    InstaSevenstore,
    PartnerSevenstore,
    FooterSevenstore

  }
};
</script>

