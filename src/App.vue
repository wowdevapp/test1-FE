<template>
  <div id="app">
      <appHeader></appHeader>
      <aboutUs></aboutUs>
  </div>
</template>
<script>
import aboutUs from './components/section/aboutUs.vue';
export default {
  name: 'App',
  components: {
    'aboutUs':aboutUs
  }
}
</script>

<style>

</style>
