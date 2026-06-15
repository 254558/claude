<template>
  <EffortCard />
</template>

<script setup>
import EffortCard from './components/EffortCard.vue';
</script>

<style>
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: #000;
  background-image: linear-gradient(rgba(255,255,255,0.05) 1px, transparent 1px),
                    linear-gradient(90deg, rgba(255, 255, 255, 0.05) 1px, transparent 1px);
  background-size: 40px 40px;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'DM Sans', -apple-system, system-ui, sans-serif;
  -webkit-font-smoothing: antialiased;
}
</style>
