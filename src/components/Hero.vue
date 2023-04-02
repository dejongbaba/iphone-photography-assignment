<script>
import PhoneCase from "../components/PhoneCase";
import HeroSignUp from "../components/HeroSignUp";
export default {
  components: {PhoneCase,HeroSignUp}
}
</script>
<template>
  <div class='hero-grid'>
    <div class='logo-section'>
      <img src="../assets/images/svgs/ips-logo.svg" alt="iphone photography logo">
    </div>
    <div class='main-section'>
      <HeroSignUp />
      <PhoneCase />
    </div>
  </div>
</template>

<style scoped>

.main-section{
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
}
.logo-section{
  grid-column-start: 1;
  grid-column-end: 4;
  padding: 3rem 0;
}


@media (min-width: 1024px) {

  .hero-grid{
    grid-template-rows: 1fr 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr;
    max-width: 80%;
     margin: 0 auto;
  }


}
</style>
