<template>
  <div>
    <a-scene embedded arjs>
      <a-box position="0 0.5 0" material="color: red;"></a-box>
      <a-marker-camera preset="hiro"></a-marker-camera>
    </a-scene>
  </div>
</template>

<script>
import "ar.js";
export default {};
</script>

<style scoped>
</style>