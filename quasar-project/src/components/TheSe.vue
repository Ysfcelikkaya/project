<template>
    <div class="q-pa-md">
      <q-carousel
        v-model="slide"
        transition-prev="scale"
        transition-next="scale"
        swipeable
        animated
        control-color="black"
        navigation
        padding
        arrows
        height="480px"
        class="col-8 text-white shadow-1 rounded-borders"
        style="background-color: #f1f1f1"
      >
        <q-carousel-slide name="1" class="column no-wrap flex-center">
          <q-img src="src\assets\images\heritage-desktop.webp"></q-img>
        </q-carousel-slide>
        <q-carousel-slide name="2" class="column no-wrap flex-center">
          <q-img src="src\assets\images\new-desktop.webp"></q-img>
        </q-carousel-slide>
        <q-carousel-slide name="3" class="column no-wrap flex-center">
          <q-img src="src\assets\images\warm_desktop.webp"></q-img>
        </q-carousel-slide>
        <q-carousel-slide name="4" class="column no-wrap flex-center">
          <q-img src="src\assets\images\facet-75-alpha-desktop.webp"></q-img>
        </q-carousel-slide>
        <q-carousel-slide name="5" class="column no-wrap flex-center">
          <q-img src="src\assets\images\essentials-desktop.webp"></q-img>
        </q-carousel-slide>
      </q-carousel>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        slide: 0,
      };
    },
  };
  </script>
  
  <style scoped>
  </style>
  