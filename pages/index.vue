<template>
  <div class="container">
    <Carousel :carousel_data="sliderItems" :slideWidth="300" />
  </div>
</template>

<script>
import Carousel from "~/components/Carousel";

export default {
  data() {
    return {
      sliderItems: [
        { id: 1, name: "img1", img: "1.jpg" },
        { id: 2, name: "img2", img: "2.jpg" },
        { id: 3, name: "img3", img: "3.jpg" },
        { id: 4, name: "img4", img: "4.jpg" },
        { id: 5, name: "img5", img: "5.jpg" }
      ]
    };
  },
  components: {
    Carousel
  }
};
</script>

<style>
</style>
