<template>
  <div>
    <h1>{{ titulo }}</h1>
    <img :src="foto.url" v-bind:alt="foto.titulo">
  </div>
</template>

<script>
export default {
 data() {
   return {
     titulo: 'Alurapic',
     foto: {
       url: 'https://www.petz.com.br/blog/wp-content/uploads/2021/03/piercing-para-cachorro-2.jpg',
       titulo: 'cachorro sorrindo'
     }
   }
 }
}
</script>

<style>

</style>
