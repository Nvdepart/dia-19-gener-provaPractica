<template>
    <v-card 
    tile
    rounded-lg
    class="pa-md-10 pa-5 text-center"
    color="surface">
    <h4>Atlas-Expo</h4>
    <div>
        <v-btn 
        v-for="(s, i) in sm" 
        :key="`socialMedia-${i}`" 
        fab 
        icon
        size="20"
        >
        <v-icon>{{s.icon}}</v-icon>
    </v-btn>
            
            <p>&copy; {{ new Date().getFullYear() }}</p>
        </div>
      </v-card>
</template>

<script>
export default {
   data(){
    return{
        sm:[
            {icon:"mdi-facebook", link:"www.faceboock.com"},
            {icon:"mdi-twitter", link:"www.twitter.com"},
            {icon:"mdi-instagram", link:"www.instagram.com"},
            {icon:"mdi-youtube", link:"www.youtube.com"},
        ]
    }
   }
}
</script>

<style lang="scss" scoped>

</style>