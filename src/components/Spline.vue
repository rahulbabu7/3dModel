<script setup>
  import { ref } from 'vue';
  import Spline from "spline-vue/v3";
  
  const scene = ref("https://prod.spline.design/B8VUB2EtZd6u0F9b/scene.splinecode");
  </script>
  
  <template>
    <Spline :scene="scene" class="spline" />
  </template>

  <style scoped>
 .spline{
  

  align-items: center;
  /* background: transparent; */
  overflow: visible;
 }
</style>