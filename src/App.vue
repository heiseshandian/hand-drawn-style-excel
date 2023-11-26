<script setup lang="ts">
</script>

<template>
  <div class="flex flex-column height-100">
    <div class="excel-bars">
      <div class="menubars"></div>
      <div class="toolbars"></div>
    </div>

    <div class="excel-editor border-1 height-100"></div>
  </div>
</template>

<style lang="scss" scoped>
@import '@/assets/variables.scss';

.excel-bars {
  background-color: rgb($menubar-background-color, 0.3);

  .menubars {
    height: 33px;
  }

  .toolbars {
    background-color: $menubar-background-color;
    border: none;
    border-radius: 24px;
    margin: 6px 16px 8px 16px;
    min-height: 40px;
    padding: 0 8px;
    -webkit-font-smoothing: antialiased;
  }
}
</style>
