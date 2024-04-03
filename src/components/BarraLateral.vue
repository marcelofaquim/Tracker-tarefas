<template>  

    <header>
        <h1>
            <img src="../assets/Logo marca Marcelo.png" alt="">
        </h1>
    </header>

</template>

<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent ({
    name: 'BarraLateral'

})

</script>

<!-- todo o estilo do componete esta abaixo  -->

<style scoped>

header {
    background: aqua;
    width: 100%;
    height: 100vh;
}

@media only screen and (max-widht: 768px) {
    header {
        padding: 2.5em;
        height: auto;
    }    
}

</style>