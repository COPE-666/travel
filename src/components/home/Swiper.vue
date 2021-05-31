<!--<template>-->
<!--  <swiper  :options="swiperOptions">-->
<!--    <swiper-slide>Slide 1</swiper-slide>-->
<!--    <swiper-slide>Slide 2</swiper-slide>-->
<!--    <swiper-slide>Slide 3</swiper-slide>-->
<!--    <swiper-slide>Slide 4</swiper-slide>-->
<!--    <swiper-slide>Slide 5</swiper-slide>-->
<!--    <div class="swiper-pagination" slot="pagination"></div>-->
<!--  </swiper>-->
<!--</template>-->

<template>
  <div class="block">
<!--    <span class="demonstration">默认 Hover 指示器触发</span>-->
    <el-carousel height="150px">
      <el-carousel-item v-for="item in 4" :key="item">
        <img  v-if="item === 1" src="../../assets/styles/img/1.png" alt="图片1">
        <img v-if="item === 2" src="../../assets/styles/img/2.png" alt="图片2">
<!--&lt;!&ndash;        <h3 class="small">{{ item }}</h3>&ndash;&gt;-->
      </el-carousel-item>
    </el-carousel>
  </div>
</template>
<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOptions: {}
    }
  }
}
</script>

<!--<style scoped>-->

<!--</style>-->
<style>
  .el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 150px;
    margin: 0;
  }

  .el-carousel__item img{
    width: 375px;
  }

  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }

  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
</style>
