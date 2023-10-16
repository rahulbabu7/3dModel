<!-- SplineEmbed.vue -->
<template>
  <div>
   
    <!-- Embed Spline Project -->
    <iframe
      :src="splineProjectUrl"
en
    ></iframe>
  </div>
</template>

<script setup>
const splineProjectUrl =
  "https://my.spline.design/planetearthdaycopy-2333a6dda7fecbc7779226b36abe6285/";
</script>

<style scoped>

iframe{
  width:100vw;
      height:100vh;

}
</style>
