<template>
    <v-app-bar app color="#111111" dark flat>
        <v-btn nuxt to="/">SMO</v-btn>
        <v-spacer></v-spacer>    
        <v-btn nuxt to="/">Inici</v-btn>
        <v-btn text nuxt to="/empresa">Empresa </v-btn>
        <v-btn text nuxt to="/productes">Productos</v-btn>
        <v-btn text nuxt to="/privacitat">Privacitat</v-btn>
        <v-btn text nuxt to="/contacte">Contacte</v-btn>
       </v-app-bar>
</template>

<script>
export default {
   
}
</script>

<style lang="scss" scoped>

</style>