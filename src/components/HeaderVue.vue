<template>
    <v-container class="">
    <v-row no-gutters>
      <v-col>
        <div class="text-h1 align-lg-start">Ian</div>
        <div class="text-h1">Veilleux</div>
      </v-col>
      <v-col class="align-lg-end">
        <div class="hdr-images">
          <img :src="ianveiIcon" alt="" class="ianveiIcon">
        </div>
        <div class="hdr-text">
          <p class="font-weight-regular mb-2">Normal weight text.</p>
          <p class="font-weight-regular">Normal weight text.</p>
          <p class="font-weight-regular">Normal weight text.</p>
          <p class="font-weight-regular">Normal weight text.</p>
        </div>
      </v-col>

    </v-row>
  </v-container>
</template>

<script setup>
  import HelloWorld from '@/components/HelloWorld.vue'
  import ianveiIcon from '../assets/ianveiicon.png'
</script>

<style scoped>
  .ianveiIcon{
    max-width: 3rem;
  }
</style>