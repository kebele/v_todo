<template>
  <div class="home">
    <h1>homepage</h1>
    <!-- spacing - margin-padding -->
    <!-- m margin, p padding bootstrap gibi kullanımı var, sm small screen gibi,   -->
        <h3>margin - padding - spacing</h3>
    <v-row>
      <h3 class="ml-sm-12">ml small screen</h3>
      <h3 class="ml-10">margin left</h3>
      <h3 class="mx-auto">Spacing</h3>
    </v-row>
    <br />
    <!-- buttons  -->
    <v-row class="ml-15">
      <h3>buttons</h3>

      <v-row class="mt-5 mb-5">
        <v-col cols="12">
          
            <v-btn small outlined block>submit</v-btn>
          
          
            <v-btn class="red white--text" small rounded>submit</v-btn>
    <v-col>
        <v-btn fab color="warning">
                <v-icon>mdi-pencil</v-icon>
            </v-btn>
    </v-col>
            
          
        </v-col>
      </v-row>
    </v-row>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>
