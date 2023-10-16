<!-- SplineEmbed.vue -->
<template>
  <div>
    <h2>
      hi   brpooooo
    </h2>
    <!-- Embed Spline Project -->
    <iframe :src="splineProjectUrl"></iframe>
  </div>
</template>

<script setup>
const splineProjectUrl =
  "https://my.spline.design/planetearthdaycopy-2333a6dda7fecbc7779226b36abe6285/";
</script>

<style scoped>
div {
  position: relative;
}

iframe {
  width: 100vw;
  height: 100vh;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1;
}

h2 {
  z-index: 2;
  color: red;
  position: relative; /* Ensure the z-index works by giving position other than static */
  margin: 0;
}
</style>
