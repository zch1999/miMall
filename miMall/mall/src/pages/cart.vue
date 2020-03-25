<!--  -->
<template>
  <div>
    <order-header></order-header>
      我是一个cart
    <nav-footer></nav-footer>
  </div>
</template>

<script>
import OrderHeader from './../components/OrderHeader'
import NavFooter from './../components/NavFooter'
export default {
  name: 'cart',
  components:{
      OrderHeader,
      NavFooter
  },
  data () {
    return {
    }
  }
}
</script>

<style lang='stylus' scoped>

</style>
