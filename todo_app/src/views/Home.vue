<template>
  <div class="home">
    <h1>homepage</h1>
    <!-- buton ve icon kullanımı -->

    <v-btn class="green white--text">click me</v-btn>
    <v-btn depressed color="green">click me</v-btn>
    <v-btn flat color="green">click me</v-btn>

    <v-btn depressed class="pink white--text">
        <v-icon left>mdi-email</v-icon>
        <span>email me</span>
    </v-btn>

    <v-btn depressed small class="blue white--text">
        <v-icon left small>mdi-email</v-icon>
        <span>email me</span>
    </v-btn>

    <v-btn depressed large class="orange white--text">
        <span>email me</span>
        <v-icon right large>mdi-email</v-icon>
    </v-btn>
<!-- https://cdn.materialdesignicons.com/5.4.55/ -->
    <v-btn fab depressed small dark color="purple">        
        <v-icon large>mdi-heart</v-icon>
        <!-- <v-icon large>mdi-Heart-Multiple</v-icon> -->
        
    </v-btn>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
 
}
</script>
