<template>
  <div>
    <TopBar></TopBar>
    <!-- <router-view/> -->
  </div>
</template>

<script lang="ts">

import { defineComponent } from "vue";
import TopBar from "@/views/_layout/TopBar.vue";

export default defineComponent({
  components: {
    TopBar,
  },
  setup() {
    return {};
  },
});
</script>

<style scoped>
</style>