<template>
  <div id="app">
    <tab-bar-index></tab-bar-index>
    <router-view></router-view>
  </div>
</template>

<script>
import TabBarIndex from './components/tabbar/TabBarIndex.vue';
export default {
  name: "App",
  components: {
    TabBarIndex

  },
};
</script>

<style>
@import url(./assets/css/base.css);
</style>
