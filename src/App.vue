<script setup lang="ts">
import { World, Cube } from "lingo3d-vue"
</script>

<template>
  <World>
    <Cube :animation="{ rotationY: [0, 180, 360] }" />
  </World>
</template>