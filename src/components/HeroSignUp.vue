<template>
  <div class='hero-text-section'>
  <div class='hero-pill'>New course</div>
  <h1 class='hero-heading'>iPhone Photo Academy</h1>
  <p class='hero-heading'>Sign up now to get notified when this course is available!</p>
  </div>
</template>

<style scoped>

.hero-text-section{

}
.hero-pill{
  background-color: var(--vt-c-green);
  padding: 8px 16px 8px 16px;
  border-radius: 32px;
}


@media (min-width: 1024px) {

  .hero-grid{
    grid-template-rows: 1fr 1fr 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    max-width: 80%;
     margin: 0 auto;
  }


}
</style>
