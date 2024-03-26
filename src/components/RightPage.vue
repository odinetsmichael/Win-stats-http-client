<script setup>
  import LineChart from './LineChart.vue'
</script>

<template>
  <div class="information">

    <div class="information__title">
      <h4>
        CPU: Intel Core i7-9750H [/intelcpu/0]
      </h4>
    </div>

    <div class="sensor-types">

      <ul class="sensor-types__list">

        <li class="sensor-types__item">
          <div class="sensor-types__title">
            <h5>Temperature</h5>
          </div>
          <LineChart/>
        </li>

        <li class="sensor-types__item">
          <div class="sensor-types__title">
            <h5>Temperature</h5>
          </div>
          <LineChart/>
        </li>

        <li class="sensor-types__item">
          <div class="sensor-types__title">
            <h5>Temperature</h5>
          </div>
          <LineChart/>
        </li>

      </ul>
      
    </div>
  </div>
</template>

<style scoped lang="scss">
  .information{
    width: 70%;
    border: 2px solid black;
    padding: 5px;
    &__title{
      text-align: center;
    }
  }

</style>
