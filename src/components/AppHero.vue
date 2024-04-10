<script>
    import AppTitle from './AppTitle.vue';
    export default {
        name: 'AppHero',
        components: {
          AppTitle,
        }
  }
</script>

<template>
    <div class="container">
        <AppTitle></AppTitle>
    </div>
</template>

<style scoped>
    .container {
        width: 62.5rem;
        height: 31.25rem;
        margin: .625rem auto;
        background-image: url(../assets/dragon-quest-xi-s.jpg);
        background-size: cover;
        background-position: center;
        color: #ffffff;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    h1 {
        font-size: 3.125rem;
    }
</style>