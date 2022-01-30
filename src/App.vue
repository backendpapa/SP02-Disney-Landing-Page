<template>
  <v-app>
    <v-app-bar
    class="pa-2"
      fixed
      color="transparent"
      flat
    >
      <div class="d-flex align-center">
       <p><v-img src="./assets/images/Logo.png"></v-img></p>
      </div>

  <div class="d-none d-sm-flex">
     <div style="margin-left:10%"  class="d-flex align-center">
     <v-btn  small plain text style="text-transform:none" class="font-3 weight-500 white--text"><v-icon size="18">mdi-home</v-icon> <span class="mb-n1">HOME</span></v-btn>
      <v-btn small plain text style="text-transform:none" class="font-3 weight-500 white--text"><v-icon size="18">mdi-magnify</v-icon> <span class="mb-n1">SEARCH</span></v-btn>
       <v-btn small plain text style="text-transform:none" class="font-3 weight-500 white--text"><v-icon size="18">mdi-plus</v-icon> <span class="mb-n1">WATCHLIST</span></v-btn>
       <v-btn small plain text style="text-transform:none" class="font-3 weight-500 white--text"><v-icon size="18">mdi-star</v-icon> <span class="mb-n1">ORIGINALS</span></v-btn>
       <v-btn small plain text style="text-transform:none" class="font-3 weight-500 white--text"><v-icon size="18">mdi-movie-star-outline</v-icon> <span class="mb-n1">MOVIES</span></v-btn>
       <v-btn small plain text style="text-transform:none" class="font-3 weight-500 white--text"><v-icon size="18">mdi-wallet-giftcard</v-icon> <span class="mb-n1">SERIES</span></v-btn>
       
      </div>
  </div>
      <v-spacer></v-spacer>

     
        <v-app-bar-nav-icon class="white--text d-flex d-sm-none" />
     
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import "./css/fonts.css"
export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
<style>
.weight-500{
  font-weight: 500 !important;
}
</style>
