<template>
  <div>
    <the-navbar />
    <nuxt />
    <the-footer />
  </div>
</template>

<script>
import TheNavbar from '@/components/TheNavbar'
import TheFooter from '@/components/TheFooter'

export default {
  components: {
    TheNavbar,
    TheFooter
  }
}
</script>

<style lang="scss">
 @import '@/assets/styles/main.scss';
</style>
