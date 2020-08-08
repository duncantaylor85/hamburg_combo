<template>
  <div id="navbar">
    <v-app-bar dark app flat color="blue-grey darken-4">
      <v-app-bar-nav-icon class="hidden-md-and-up" @click="drawer = !drawer">
      </v-app-bar-nav-icon>
      <v-spacer></v-spacer>
      <v-btn color="grey lighten-2" x-large class="hidden-sm-and-down" text v-scroll-to="'#hochzeit'"
        >Hochzeiten</v-btn
      >
      <v-btn color="grey lighten-2" x-large class="hidden-sm-and-down" text v-scroll-to="'#geburtstag'"
        >Geburtstag</v-btn
      >
      <v-toolbar-title>
        <a
          class="text-uppercase mx-12 mb-12 display-1 grey--text text--lighten-2"
          v-scroll-to="'#welcome'"
          >Hamburg Combo</a
        >
      </v-toolbar-title>
      <v-btn color="grey lighten-2" x-large class="hidden-sm-and-down" text v-scroll-to="'#ueberuns'"
        >Über Uns</v-btn
      >
      <v-btn color="grey lighten-2" x-large class="hidden-sm-and-down" text v-scroll-to="'#kontakt'"
        >Kontakt</v-btn
      >

      <v-spacer></v-spacer>
    </v-app-bar>

    <v-navigation-drawer width="200" app temporary v-model="drawer">
      <v-list dense nav>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title class="title pb-1 text-center">
              Menu
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-divider></v-divider>
        <v-list-item
          link
          v-for="link in links"
          :key="link.text"
          v-scroll-to="link.scrollto"
        >
          <v-list-item-action class="mr-3"
            ><v-icon>{{ link.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>{{ link.text }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      drawer: false,
      links: [
        {
          icon: "mdi-heart-multiple",
          text: "Hochzeiten",
          scrollto: "#hochzeit"
        },
        {
          icon: "mdi-party-popper",
          text: "Geburtstag",
          scrollto: "#geburtstag"
        },
        {
          icon: "mdi-information",
          text: "Über Uns",
          scrollto: "#ueberuns"
        },
        {
          icon: "mdi-phone",
          text: "Kontakt",
          scrollto: "#kontakt"
        }
      ]
    };
  }
};
</script>

<style scoped>

</style>