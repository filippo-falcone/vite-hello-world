<script>
    export default {
        name: 'AppTitle',
        data() {
            return {
                title: ''
            }
        },
        methods: {
            helloWorld(){
                this.title = 'Hello World';
            }
          }
    }
</script>

<template>
    <h1>{{ title }}</h1>
    <button @click="helloWorld">Saluta</button>
</template>

<style scope>
    h1{
        font-size: 4.375rem;
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
    }
</style>