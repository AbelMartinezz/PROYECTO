<template >
  <v-container class="background-image-container">
    <AppBar />
    <Card />
    <Footer></Footer> 
  </v-container>
    
</template>
  
    
    <script setup>
    
    import AppBar from "../index/components/app-bar.vue"
    import Card from "./components/card.vue"
    import Footer from "../index/components/footer.vue"

    const items = ref([
      {
        titulo: "Producto 1",
        subtitulo: "Categoria a",
        text: "Lorem itsum"
        },
        {
          titulo: "Producto 1",
        subtitulo: "Categoria a",
        text: "Lorem itsum"
        },
        {
          titulo: "Producto 1",
        subtitulo: "Categoria a",
        text: "Lorem itsum"
        }])


    </script>

<style scoped>
.background-image-container {
  background-image: url('fondo5.jpg');
  background-repeat: repeat;
  background-size: contain;
  background-position: center;
}
</style>

    