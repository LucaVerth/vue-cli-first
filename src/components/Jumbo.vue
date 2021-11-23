<template>
  <div class="jumbotron">
    <img src="https://c4.wallpaperflare.com/wallpaper/581/793/198/alps-aosta-autumn-breuil-cervinia-wallpaper-preview.jpg" alt="">
    <Imagetext/>
  </div>
</template>

<script>
import Imagetext from "./Imagetext.vue"
export default {
  components: {
    Imagetext
  }
}
</script>

<style>
.jumbotron {
  position: relative;
  width: 100%;
  height: 450px;
  margin-top: 30px;
}
img{
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>