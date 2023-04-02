<template>
  <div class="phone-case">

    <div class='phone-body'>
      <img src="../assets/images/jpgs/iPhone-mokup.png" alt="iphone mockup ">
      <div class="camera-icons">

      </div>
      <div class='carousel-photo'>
        <img src="../assets/images/jpgs/small-carousel-photo-04.jpg" alt="carousel photo ">
      </div>
    </div>


    <div class='indicators'>
      <div class='step-one'></div>
      <div class='step-two'></div>
      <div class='step-three'></div>
      <div class='step-four'></div>
    </div>
  </div>
</template>

<style scoped>
.phone-case {



}
.carousel-photo{
  position: absolute;
  left: 20%;
  bottom: 10%;
}
.phone-body{
 position: relative;
}
.indicators{
  margin-top: 2rem;
  display: flex;
  justify-content: space-around;
}
.indicators div{
  background: var(--vt-c-white);
  width: 20px;
  height: 4px;
}
@media (min-width: 1024px) {

}
</style>
