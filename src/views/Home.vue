<template>
  <div class="pdf-container" style="width: 100%">
    <VuePdfEmbed
      source="https://res.cloudinary.com/dpm5vdakr/image/upload/v1714194098/Clementine_Villongco_Portfolio_compressed_l02smq.pdf"
      style="width: 100%"
    />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.vue-pdf-embed__page {
  width: 100% !important;
}
</style>
