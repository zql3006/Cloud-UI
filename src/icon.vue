<template>
  <svg class="c-icon">
    <use :xlink:href="`#c-${name}`" />
  </svg>
</template>
<script>
export default {
  props:['name']
}
</script>
<style lang="scss">
.c-icon{
  width: 1em;
  height: 1em;
}
</style>