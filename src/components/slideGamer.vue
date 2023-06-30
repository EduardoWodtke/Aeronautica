<script setup>

</script>

<template>
  <div id="carouselExampleCaptions" class="carousel slide">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner tx-color">
      <div class="carousel-item active">
        <img src="./imagensSlide/imagem01.jpg" class="fotos-slides d-block" alt="...">
        <div class="tx-color carousel-caption d-none d-md-block">
          <h5>Com AeroCompany...</h5>
          <p>Sua familia fica feliz.</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="./imagensSlide/imagem02.jpg" class="fotos-slides d-block" alt="...">
        <div class="tx-color carousel-caption d-none d-md-block">
          <h5>Com AeroCompany...</h5>
          <p>voos de qualidade.</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="./imagensSlide/imagem03.jpg" class="fotos-slides d-block" alt="...">
        <div class="tx-color carousel-caption d-none d-md-block">
          <h5>Com AeroCompany...</h5>
          <p>conheça o mundo inteiro.</p>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>

<style scoped>
.fotos-slides {
  display: flex;
  width: 100% !important;
  height: 450px !important;
  align-items: center;
}

.tx-color{
  color: #ffffff;
  font-weight: bold;  
  text-shadow: 5px 3px 4px black;
}
</style>