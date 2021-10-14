<template>
  <v-app>
    <v-app-bar app color="success" dark>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-spacer></v-spacer>
      <v-toolbar-title>동은이 첫 프로그램 </v-toolbar-title>
    </v-app-bar>

    <v-content>
      <router-view />
    </v-content>
    <v-footer color="success" dark>
      <v-bottom-navigation class="success" v-model="select">
        <v-btn text value="1학년"> 1학년</v-btn>
        <v-btn text value="2학년"> 2학년</v-btn>
        <v-btn text value="3학년"> 3학년</v-btn>
      </v-bottom-navigation>
      <div class="mx-auto">copyright by 김동은</div>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
