
<template>
  <v-bottom-navigation app fixed grow color="primary">
    
    <v-btn value="code" :to="{ name: 'News' }">
      <span>News</span>
      <v-icon color="blue" large> mdi-account </v-icon>
    </v-btn>

    <v-btn value="favorites" :to="{ name: 'Qrkeep' }">
      <span>QR KEEP</span>
      <v-icon color="blue" large> mdi-face-woman </v-icon>
    </v-btn>
    <v-btn value="Scan" :to="{ name: 'Scan' }">
      <span>Scan</span>
      <v-icon color="blue" large> mdi-qrcode </v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>

<script>
export default {
  name: "BottomNav",
  data: () => ({
    drawer: null,
  }),
};
</script>
