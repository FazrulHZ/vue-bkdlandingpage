<template>
  <div>
    <!-- <v-row>
      <v-col cols="12">
        <Chighlight />
      </v-col>
    </v-row> -->

    <div class="mt-8 mb-5">
      <CBeritautama />
    </div>

    <div class="mt-8 mb-5">
      <v-row>
        <v-col cols="12" md="8">
          <CBeritareguler />
        </v-col>
        <v-col cols="12" md="4">
          <CPengumuman />
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
// import Chighlight from "@/components/frontend/Highlight";
import CBeritautama from "@/components/frontend/Beritautama";
import CBeritareguler from "@/components/frontend/Beritareguler";
import CPengumuman from "@/components/frontend/Pengumuman";

export default {
  components: {
    // Chighlight,
    CBeritautama,
    CBeritareguler,
    CPengumuman,
  },

  data: () => ({}),
};
</script>
