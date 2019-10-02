<template lang="pug">
  #app
    p(v-show="showValue") {{value}}
</template>

<script>
export default {
  name: 'app',
  
  data () {
    return {
      msg: 'UVA', 
      showValue: false, 
      value: 'Algo'
      
    }
  }
}
</script>

<style lang="scss">

@import './assets/scss/main.scss'
</style>
