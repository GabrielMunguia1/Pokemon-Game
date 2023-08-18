<script lang="ts">
    import PokemonOptions from '@/components/PokemonOption.vue';
    import PokemonPicture from '@/components/PokemonPicture.vue';

    export default {
        components: { PokemonOptions, PokemonPicture}
    }

</script>

<template>
    <h1>¿Quien es es pokemon?</h1>
    <PokemonPicture :pokemonId="1" :showPokemon="true"/>
    <PokemonOptions/>


</template>

<style>

</style>