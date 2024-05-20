<template>
      <v-app-bar color="black" app>
        
        <v-btn text @click="goTo('/')">NHOT</v-btn>
        <v-spacer></v-spacer>
        <v-btn text @click="goTo('/about')">About</v-btn>
  
        <v-btn text @click="goTo('/products')">Products</v-btn>

        <v-btn text @click="goTo('/contacts')">Contacts</v-btn>
      </v-app-bar>
  </template>

<script>
export default {
    methods: {
        goTo(route) {
            this.$router.push(route)
        }
    }
}
</script>