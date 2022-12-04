<!-------------
      APP 
-------------->
<template>

  <div class="row">
    <div class="col-8">
      <AppTitle></AppTitle>
    </div>
    <div class="col-4">
      <AppHero></AppHero>
    </div>
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