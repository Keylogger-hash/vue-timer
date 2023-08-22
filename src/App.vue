<template>
  <div class="container">
    <MainTimer></MainTimer>
  </div>
</template>

<script setup lang="ts">
import MainTimer from '@/components/MainTimer.vue';

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing:grayscale;
  color: #2c3e50;
  width: 100%;
  height: 100%;
}
.container{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 90vh;

}
</style>
