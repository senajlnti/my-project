<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://grossmontcenter.com/wp-content/uploads/2021/09/Empire-Beauty-Supply-Header.jpg',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://bisnismuda.id/assets/content/20201019124602000000BlueGreenLoadingIconWebDesignerBusinesscard9.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': 'https://img4.thuthuatphanmem.vn/uploads/2020/12/25/anh-bia-nhung-my-pham-cuc-dep_094453730.jpg',
    'alt': 'Picture 3',
  },
  {
    'src': 'https://www.amorebeautyy.com/wp-content/uploads/2016/05/grid-3.jpg',
    'alt': 'Picture 4',
  },
  {
    'src': 'https://woww.cc/wp-content/uploads/2019/05/2851-6.jpg',
    'alt': 'Picture 5',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>
