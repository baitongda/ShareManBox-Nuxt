<style lang="scss">
  .view {
    display: flex;
    min-height: 100vh;
    flex-direction: column;
    background-color: #fff;
  }
</style>

<template>
  <div class="view">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'LayoutView'
}
</script>
