<template>
  <div class="landing-page">
    <LandingCom />
  </div>
  <div class="about-page">
    <AboutCom />
  </div>
</template>

<script>
import LandingCom from '@/components/LandingCom.vue';
import AboutCom from '@/components/AboutCom.vue';

export default {
  name: 'HomeView',
  components: {
    LandingCom,
    AboutCom,
  }
}
</script>
<style>
.landing-page{
  min-height: 100vh;
  background-color: rgba(0, 0, 0, 0.3);
}
.about-page{
  min-height: 100vh;
  background-image: linear-gradient(rgba(0,0, 0, 0.3) 0.3%, rgba(255, 255, 255, 1) 4%, rgba(255, 255, 255, 1));
}
</style>
