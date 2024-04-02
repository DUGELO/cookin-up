<script lang="ts">
    import Banner from './components/Banner.vue';
    import ConteudoPrincipal from './components/ConteudoPrincipal.vue';
    import Rodape from './components/Rodape.vue'

    export default {
        components: {
            Banner: Banner,
            ConteudoPrincipal: ConteudoPrincipal,
            Rodape: Rodape
        }
    }
</script>

<template>
    <Banner />
    <ConteudoPrincipal />
    <Rodape />
</template>

<!-- A propriedade 'scoped' dentro da tag 'style' serve para definir o escopo
    de tudo oq estiver dentro desse style, ou seja nesse nosso exemplo abaixo,
    apenas o arquivo 'App.vue' vai ser alterado com o código que colocarmos dentro de style-->
<style scoped>



</style>
