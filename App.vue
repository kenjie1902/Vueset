<template>
  <div>
    <h1>My Vue.js App with Chart.js</h1>
    <MyChart />

    <h1>My Acqui Chart</h1>
    <AcquisitionsChart />
  </div>
</template>

<script setup>
import AcquisitionsChart from './components/AcquisitionsChart.vue';
import MyChart from './components/MyChart.vue';
</script>
