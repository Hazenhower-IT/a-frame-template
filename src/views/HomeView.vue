<template>
  <div>
    <a-scene>
      <a-sphere position="0 1.25 -5" radius="1.25" color="red"></a-sphere>
      <a-box position="-1 0.5 -3" rotation="0 45 0" width="1" height="1" depth="1" color="blue"></a-box>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="green"></a-plane>
      <a-sky color="#87CEEB"></a-sky>
      <a-camera look-controls wasd-controls cursor="rayOrigin: mouse"></a-camera>
      <a-light type="point" position="2 4 4" intensity="0.5"></a-light>
    </a-scene>
  </div>
</template>

<script setup>
</script>
