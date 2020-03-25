<!--  -->
<template>
  <div>
    <service-bar></service-bar>
  </div>
</template>

<script>
import ServiceBar from './../components/ServiceBar'
import { swiper, swiperSlide } from 'vue-awesome-swiper'
export default {
  name: 'index',
  components: {
      swiper,
      swiperSlide,
      ServiceBar,
  },
  data () {
    return {
    }
  }
}
</script>

<style lang='stylus' scoped>

</style>
