<script setup>
  import LeftPage from './LeftPage.vue';
  import RightPage from './RightPage.vue';
</script>

<template>
  <div class="overwiew">
    <LeftPage/>
    <RightPage/>
  </div>
</template>

<style scoped>
  .overwiew{
    display: flex;
    width: 100%;
    padding: 50px;
  }
</style>
