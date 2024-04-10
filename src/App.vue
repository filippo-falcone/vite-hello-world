<script>
  import AppTitle from './components/AppTitle.vue';
  export default {
    components: {
      AppTitle
    }
  }
</script>

<template>
  <main>
    <AppTitle></AppTitle>
  </main>
</template>

<style>
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
</style>