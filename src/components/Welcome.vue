<template>
  <div id="welcome">
    <v-img min-width="420" src="../assets/P10100660b.jpg">
      <v-row style="height: 600px;" justify="space-around">
        <v-col align-self="end" cols="2">
          <v-card-actions class="justify-center">
            <v-btn  outlined  v-scroll-to="'#kontakt'" color="deep-orange" x-large>Buchen Sie uns!</v-btn>
          </v-card-actions>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="d-flex justify-center">
          <v-btn x-large href="https://www.youtube.com/channel/UC7zTuLQ3XWC-lXbacqCjjQg" target="_blank" color="red" icon class="mx-2">
            <v-icon x-large>mdi-youtube</v-icon>
          </v-btn>

          <v-btn href="https://www.facebook.com/hamburg.combo/" target="_blank" x-large color="blue" icon class="mx-2">
            <v-icon x-large>mdi-facebook</v-icon>
          </v-btn>
        </v-col>
      </v-row>
    </v-img>
  </div>
</template>

<script>
export default {
  name: "Welcome",
};
</script>

<style>
.btn {
  border: 2px solid black !important;
}

a {
  text-decoration: none;
}
</style>
