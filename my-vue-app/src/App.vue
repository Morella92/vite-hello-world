<script>
//importo il componente
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default{
  components: {
    //registro il componente
    AppTitle,
    AppHero
  },
}
</script>

<template>

  <div class="bg-image">
    
  </div>

  <!-- utilizzo il componente e stampo il titolo -->
  <!-- <AppTitle></AppTitle> -->
  <AppHero></AppHero>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

</style>
