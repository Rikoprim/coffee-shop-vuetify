<template>
  <v-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <SideBar />
    <SideBarRight />
    <v-container>
      <v-toolbar color="rgba(0,0,0,0)" flat>
        <v-toolbar-title class="mt-n3">Choose Category</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-text-field
          label="Search category or menu..."
          class="mt-5"
          color="brown"
          filled
          append-icon="mdi-magnify"
          dense
          solo
          flat
          background-color="grey lighten-4"
        ></v-text-field>
      </v-toolbar>
      <v-item-group mandatory class="mt-n1">
        <v-container>
          <Category />
        </v-container>
      </v-item-group>
      <v-toolbar color="#EEEEEE" flat>
        <v-toolbar-title>Coffee Menu</v-toolbar-title>
        <v-spacer></v-spacer>
        <span color="grey">12 Coffees Result</span>
      </v-toolbar>
      <Menus />
    </v-container>
  </v-app>
</template>

<script>
import SideBar from "../components/SideBar";
import SideBarRight from "../components/SideBarRight";
import Category from "../components/Category";
import Menus from "../components/Menus";

export default {
  name: "Home",

  components: {
    SideBar,
    SideBarRight,
    Category,
    Menus,
  },
};
</script>

<style scoped>
.v-card.borderme {
  border: 2px solid #704232 !important;
}
.v-card.borderout {
  border: 1px solid #bcaaa4 !important;
}
</style>
