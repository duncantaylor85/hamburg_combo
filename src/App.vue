<template>
  <div id="app">
    <v-app>
      <v-content app>
        <Navbar />
        <Welcome />
        <v-container fluid>
          <Hochzeit />
          <Geburtstag />
          <UeberUns />
          <Kontakt />
        </v-container>
      </v-content>
      <Footer />
    </v-app>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";
import Hochzeit from "@/components/Hochzeit";
import Geburtstag from "@/components/Geburtstag";
import UeberUns from "@/components/UeberUns";
import Welcome from "@/components/Welcome";
import Kontakt from "@/components/Kontakt";
import Footer from "@/components/Footer";

export default {
  name: "App",

  components: {
    Navbar,
    Hochzeit,
    Geburtstag,
    UeberUns,
    Welcome,
    Kontakt,
    Footer,
  },

  data() {
    return {};
  },
};
</script>
