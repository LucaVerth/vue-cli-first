<template>
  <div class="jumbotron">
    <img src="http://localhost:8080/img/valle.af2fb78e.jpg" alt="">
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