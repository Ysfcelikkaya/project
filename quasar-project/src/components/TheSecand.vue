<template>
  <div class="q-pa-md">
    <div class="q-gutter-md row items-start">
      <q-img
        src="src\assets\images\10.png"
        srcset="src\assets\images\10.png 300w,
                src\assets\images\10.png 2x,
                src\assets\images\10.png 3x,
                src\assets\images\10.png 4x"
        style="height: 590px; max-width: 594px"
      ></q-img>

      <q-img
        src="src\assets\images\New1-desktop.webp"
        srcset="src\assets\images\New1-desktop.webp 400w,
                src\assets\images\New1-desktop.webp 800w,
                src\assets\images\New1-desktop.webp 1200w,
                src\assets\images\New1-desktop.webp 1600w"
        sizes="(max-width: 400px) 400w,
                (min-width: 400px) and (max-width: 800px) 800w,
                (min-width: 800px) and (max-width: 1200px) 1200w,
                (min-width: 1200px) 1600w"
        style="height: 590px; max-width: 594px"
      ></q-img>
    </div>
  </div>
</template>

<script>
export default {
};
</script>

<style scoped>
</style>
