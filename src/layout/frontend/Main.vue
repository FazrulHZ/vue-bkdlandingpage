<template>
  <v-app id="inspire">
    <Header />

    <Menu />

    <v-main style="background: #EEEEEE;">
      <v-row>
        <v-col cols="12">
          <Chighlight />
        </v-col>
      </v-row>
      <v-container>
        <router-view />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import Header from "@/layout/frontend/Header";
import Menu from "@/layout/frontend/Menu";

import Chighlight from "@/components/frontend/Highlight";

export default {
  components: {
    Header,
    Menu,

    Chighlight,
  },
  data: () => ({ drawer: null }),
};
</script>
