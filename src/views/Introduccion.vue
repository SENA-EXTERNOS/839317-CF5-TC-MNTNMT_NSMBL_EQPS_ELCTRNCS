<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7(data-aos="fade-right")
        p Apreciado aprendiz, sea bienvenido a este componente formativo, orientado a la disposición de residuos electrónicos. A través de este material de estudio, podrá aprender sobre los desechos y elementos asociados al mismo como la categorización, el reciclaje, la reutilización y el aprovechamiento, entre otros. También conocerá de cerca, la normatividad, el almacenamiento y las posibilidades que hay frente a la recuperación de materiales. Finalmente, se ahondará en el reconocimiento de los protocolos y las medidas de seguridad y salud en el trabajo que deberán ser contempladas cuando se realicen las actividades descritas en este componente formativo.
          br
          br
          |En el siguiente video conocerá de manera general los saberes que se desarrollan en esta guía académica.
          br
          br
          span.r--1 #[b Le deseamos una grata experiencia de aprendizaje.]
      .col-lg-5.col-6(data-aos="fade-left"): img(src='@/assets/curso/intro/1.png', alt='')
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
