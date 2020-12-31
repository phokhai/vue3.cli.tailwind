<template>
  <div>
    <TopBar></TopBar>
    <ButtonBar></ButtonBar>
    <!-- <router-view/> -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import TopBar from '@/views/_layout/TopBar.vue';
import ButtonBar from '@/views/_layout/ButtonBar.vue';

export default defineComponent({
  components: {
    TopBar,
    ButtonBar,
  },
  setup() {
    return {};
  },
});
</script>

<style scoped>
</style>