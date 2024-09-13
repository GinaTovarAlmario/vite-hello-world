<!-- 1-importo il file in cima al mio script e gli diamo un nome -->
<!-- 2-lo inserisco nella lista dei componenti -->
<!-- 2-lo inserisco come un self-closing tag in html -->
<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components:{
    AppTitle,
    AppHero
  },
  data() {
    return {
    }
  }
}
</script>
<template>
  <div>
    <AppTitle/>
  </div>
  <div>
    <AppHero/>
  </div>
</template>
<style scoped>
</style>
