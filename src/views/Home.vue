<template>
  <div>
    <div class="bg">
      <v-container>
        <v-row style="height: 100vh" no-gutters align="center" justify="center">
          <v-col cols="12" xl="6" lg="6"> </v-col>
          <v-col cols="12" xl="6" lg="6">
            <p
              class="font-1 text-align white--text"
              style="line-height: 1; font-weight: 750"
            >
              A new world to be explored
            </p>
            <p class="font-2 text-align white--text" style="font-weight: 400">
              A magical door will soon open that will take you to the wonderful
              world of Disney!
            </p>
           <p class="text-align"> <v-btn rounded  class="font-2 btn" color="red" elevation="5" dark x-large style="text-transform:none;font-weight:850;width:340px">Back to home</v-btn></p>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",

  components: {},
};
</script>
<style>
.bg {
  background: linear-gradient(
      180deg,
      rgba(0, 0, 0, 0.5) 1%,
      rgba(0, 0, 0, 0.273638) 51.03%,
      rgba(0, 0, 0, 0.5) 100%
    ),
    url("../assets/images/hero2.jpg");
  height: 100vh;
  background-size: cover;
}
.btn{
  width:340px;
}
.text-align{
  text-align: right;
}
@media screen and (max-width:600px) {
  .text-align{
    text-align: left;
  }
  .btn{
    width: 200px !important ;
  }
}
</style>
