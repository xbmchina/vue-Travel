<template>
      <transition>
            <slot></slot>
      </transition>
</template>

<script>
  export default {
      name: 'Fade'
     
  }
</script>

<style lang="stylus" scoped>
.v-enter,.v-leave-to
      opactity: 0
.v-enter-active, .v-leave-active
      transition: opactity .5%
</style>
