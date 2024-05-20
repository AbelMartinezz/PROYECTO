<template>
    <v-carousel height="600px">
      <v-carousel-item
        v-for="item in items" :key="item.key"
        :src="item.image"
        cover
      ></v-carousel-item>
      
    </v-carousel>
    </template>
    <script setup>
    
    const items = ref([
      {
        image: "/test.jpg"
      },
      {
        image: "https://cdn.vuetifyjs.com/images/cards/hotel.jpg"
      },
      {
        image: "https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      }
    ])
    
    </script>