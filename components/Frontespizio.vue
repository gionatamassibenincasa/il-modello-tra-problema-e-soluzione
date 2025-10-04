<script setup lang="ts">
import Autori from './Autori.vue';
import Piede from './Piede.vue';
import Titolo from './Titolo.vue';
import QR from './QR.vue';
</script>

<template>
  <div class="slidev-layout cover">
    <div class="my-auto w-full">
      <Titolo />
      <Autori />
    </div>
  </div>
  <QR />
  <Piede />
</template>

<style lang="css" scoped></style>
