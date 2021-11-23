<template>
  <div id="app">
    <Title/>
    <Hero/>
    <footer></footer>
  </div>
</template>

<script>
import Title from "./components/Title.vue"
import Hero from "./components/Hero.vue"

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app{
  width: 80%;
  margin: 0 auto;
  margin-top: 50px;
}
</style>
