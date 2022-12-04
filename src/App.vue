<!-------------
      APP 
-------------->
<template>
  <div>
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  data() {
    return {};
  },
  components: {
    AppTitle, 
    AppHero
  }
};
</script>

<style>

</style>