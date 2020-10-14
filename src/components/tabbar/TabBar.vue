<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'TabBar'
}
</script>

<style scoped>

  #tab-bar {
    display: flex;
    background-color: aqua;
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    box-shadow: 1px 1px 1px rgba(red, green, blue, 0.5);
  }


</style>