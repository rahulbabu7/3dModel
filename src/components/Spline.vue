<!-- SplineEmbed.vue -->
<template>
  <div>
   
    <!-- Embed Spline Project -->
    <iframe
      :src="splineProjectUrl"
      width="100%"
      height="600px"
      frameborder="0"
      allowfullscreen
    ></iframe>
  </div>
</template>

<script setup>
const splineProjectUrl =
  "https://my.spline.design/planetearthdaycopy-2333a6dda7fecbc7779226b36abe6285/";
</script>
