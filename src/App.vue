<template>
  <div id="app">
    
    <Title />

    <Hero />

  </div>
</template>

<script>
import Title from '@/components/Title.vue';
import Hero from '@/components/Hero.vue';

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">
#app{
  width: 80%;
  height: 80vh;
  background-color: rgb(234, 243, 247);
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
