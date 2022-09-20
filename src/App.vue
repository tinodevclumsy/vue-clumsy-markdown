<template>
  <div>
    <TheHeader />

    <div class="flex content-container">
      <TheEditor class="w-1/2" />
      <ThePreview class="w-1/2" />
    </div>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheEditor from './components/TheEditor.vue'
import ThePreview from './components/ThePreview.vue';

export default {
  name: "App",
  components: {
    TheHeader,
    TheEditor,
    ThePreview,
  },
};
</script>

<style>
  .content-container {
    height: calc(100vh - 50px);
  }
</style>
