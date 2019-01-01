<template>
  <div class="wrapper">
    <swiper :options="swiperOption">
      <!-- slides -->
      <swiper-slide v-for="item of swiperList" :key="item.id">
        <img :src="item.imgUrl" style="width: 100%; height: 120px;"/>
      </swiper-slide>
      <!-- Optional controls -->
      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination'
      },
      swiperList: [
        {
          id: '0001',
          imgUrl: 'http://img3.mukewang.com/szimg/5c258064096014e218000600.jpg'
        }
      ]
    }
  }
}
</script>

<style lang="stylus" scoped>
  wrapper
    width: 100%
    // height: 0
    // overflow: hidden
    // padding-bottom: 31.25%
</style>
