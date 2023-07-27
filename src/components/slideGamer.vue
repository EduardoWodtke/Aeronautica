<script setup>

</script>

<template>
  <section class="container mt-4">
    <div id="destaquesCarousel" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#destaquesCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#destaquesCarousel" data-slide-to="1"></li>
        <li data-target="#destaquesCarousel" data-slide-to="2"></li>
        <li data-target="#destaquesCarousel" data-slide-to="3"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="./imagensSlide/imagem01.jpg" class="d-block w-100" alt="Destaque 1">
        </div>
        <div class="carousel-item">
          <img src="./imagensSlide/imagem02.jpg" class="d-block w-100" alt="Destaque 2">
        </div>
        <div class="carousel-item">
          <img src="./imagensSlide/imagem03.jpg" class="d-block w-100" alt="Destaque 3">
        </div>
        <div class="carousel-item">
          <img src="./imagensSlide/imagem04.jpg" class="d-block w-100" alt="Destaque 4">
        </div>
      </div>
      <a class="carousel-control-prev" href="#destaquesCarousel" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Anterior</span>
      </a>
      <a class="carousel-control-next" href="#destaquesCarousel" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Próximo</span>
      </a>
    </div>
  </section>
</template>

<style scoped>

</style>