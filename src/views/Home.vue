<template>
  <div class="home">
    <h1>Homepage</h1>
    <p
      class="green darken-4 white--text"
    >Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, sint!</p>
    <h1 class="display-1">Hello world</h1>
    <p class="headline text-capitalize">This is a headline</p>
    <p class="subheading font-weight-bold">This is a subheading</p>
    <p class="caption font-weight-black">This is a caption</p>
    <v-btn class="red white--text">Follow me</v-btn>
    <v-btn dark depressed color="blue">Click me</v-btn>
    <v-btn depressed color="green white--text">
      <v-icon left>mdi-email</v-icon>
      <span>Email me</span>
    </v-btn>
    <v-btn depressed class="blue white--text">
      <v-icon>mdi-android</v-icon>
    </v-btn>

    <v-btn depressed large class="blue white--text">
      <v-icon large left>mdi-email</v-icon>
      <span>Email me</span>
    </v-btn>

    <v-btn text icon color="pink">
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn text icon color="indigo">
      <v-icon>mdi-star</v-icon>
    </v-btn>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>
