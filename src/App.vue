<template>
  <v-app>
    <TopToolbar></TopToolbar>  <!-- header -->

    <v-content>
      <router-view></router-view>
    </v-content>
    <BottomNav></BottomNav> <!-- footer -->
  </v-app>
</template>

<script>
import TopToolbar from "@/components/TopToolbar";
import BottomNav from "@/components/BottomNav";
export default {
  components: {
    TopToolbar,
    BottomNav,
  },
  name: "App",
  beforeCreate() {
    console.log("init");

  },
};
</script>
