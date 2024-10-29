<script setup lang="ts">
import {NCarousel, NCarouselItem} from 'naive-ui'
</script>

<template>
  <div class="main">
    <n-carousel
        slides-per-view="auto"
        :space-between="20"
        :loop="false"
        show-arrow
        draggable
    >
      <n-carousel-item style="height: 100%; width: 208px">
        <img
            class="carousel-img"
            src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel1.jpeg"
        >
      </n-carousel-item>
      <n-carousel-item style="height: 100%; width: 308px">
        <img
            class="carousel-img"
            src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel2.jpeg"
        >
      </n-carousel-item>
      <n-carousel-item style="height: 100%">
        <img
            class="carousel-img"
            src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel3.jpeg"
        >
      </n-carousel-item>
      <n-carousel-item style="height: 100%">
        <img
            class="carousel-img"
            src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel4.jpeg"
        >
      </n-carousel-item>
    </n-carousel>
    <span style="color:#fff">滑到最后一页会显示不正常</span>

  </div>
</template>

<style>
.main {
  width: 1000px;
  height: 300px;
}

img {
  height: 100%;
}
</style>