<template>
  <div class="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
    name: 'TabBar'
};
</script>

<style>
.tab-bar {
  display: flex;
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background: #fcfcfc;
  box-shadow: 0 -1px 1px rgba(100, 100, 100, 0.1);
}

</style>