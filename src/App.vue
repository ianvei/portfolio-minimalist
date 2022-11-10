<template>
  <v-app style="flex-direction:column; align-items:center ;" flex-direction="column" align-items="center">
    <v-main class="" max-width="48rem">
      <HeaderVueVue />
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script setup>
  import HelloWorld from '@/components/HelloWorld.vue'
  import HeaderVueVue from './components/HeaderVue.vue';
</script>
