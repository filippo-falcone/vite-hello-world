<script>
    export default {
        name: 'AppTitle',
        data() {
            return {
                title: '',
                visibileClass: 'visible'
            }
        },
        methods: {
            helloWorld(){
                this.title = 'Hello World';
                this.visibileClass = '';
            }
          }
    }
</script>

<template>
    <h1>{{ title }}</h1>
    <button :class="visibileClass" @click="helloWorld">Saluta</button>
</template>

<style scoped>
    h1{
        font-size: 4.375rem;
        margin-bottom: 200px
    }

    button {
        width: 6.25rem;
        height: 3.125rem;
        background-color: lightblue;
        border: none;
        border-radius: 1.25rem;
        font-size: 1.25rem;
        cursor: pointer;
        flex-shrink: 0;
        display: none;
    }

    .visible{
        display: block;
    }
</style>