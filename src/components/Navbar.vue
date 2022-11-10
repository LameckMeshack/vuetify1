<template>
  <nav>
    <v-app-bar app flat>
      <v-app-bar-nav-icon
        class="grey--text"
        @click="drawer = true"
      ></v-app-bar-nav-icon>
      <v-toolbar-title class="text-uppercase grey--text">
        <span class="font-weight-thin">Todo</span>
        <span>work</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <span>Sign Out</span>
      <v-icon right>exit_to_app</v-icon>
    </v-app-bar>
    <v-navigation-drawer v-model="drawer" app class="indigo">
      <p>Test</p>
    </v-navigation-drawer>
  </nav>
</template>

<script>
export default {
  name: "NavbarComp",
  data: () => ({
    drawer: false,
  }),
};
</script>

<style></style>
