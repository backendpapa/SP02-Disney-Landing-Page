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
     <v-btn  small plain text style="text-transform:none" class="font-head weight-500 white--text"><v-icon size="18">mdi-home</v-icon> <span class="mb-n1">HOME</span></v-btn>
      <v-btn small plain text style="text-transform:none" class="font-head weight-500 white--text"><v-icon size="18">mdi-magnify</v-icon> <span class="mb-n1">SEARCH</span></v-btn>
       <v-btn small plain text style="text-transform:none" class="font-head weight-500 white--text"><v-icon size="18">mdi-plus</v-icon> <span class="mb-n1">WATCHLIST</span></v-btn>
       <v-btn small plain text style="text-transform:none" class="font-head weight-500 white--text"><v-icon size="18">mdi-star</v-icon> <span class="mb-n1">ORIGINALS</span></v-btn>
       <v-btn small plain text style="text-transform:none" class="font-head weight-500 white--text"><v-icon size="18">mdi-movie-star-outline</v-icon> <span class="mb-n1">MOVIES</span></v-btn>
       <v-btn small plain text style="text-transform:none" class="font-head weight-500 white--text"><v-icon size="18">mdi-wallet-giftcard</v-icon> <span class="mb-n1">SERIES</span></v-btn>
       
      </div>
  </div>
      <v-spacer></v-spacer>

     <div class="d-none d-sm-flex">
       <v-btn small plain text style="text-transform:none" class="font-head weight-500 white--text"><span class="mb-n1">Profile</span> <v-avatar size="30" class="ml-2"><v-img eager src="https://images.unsplash.com/photo-1531746020798-e6953c6e8e04?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=764&q=80"></v-img></v-avatar></v-btn>
     </div>
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
