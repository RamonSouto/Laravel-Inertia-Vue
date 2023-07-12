<template>
    <div>
        <h1>Estou na Página About</h1>
        <h2>Olá {{ name }}</h2>
        <h2>Estou no curso de {{ curso }}</h2>
    </div>
</template>
<script>

    export default {
        name: 'PageAbout',
        props:{
            name: String,
            curso: String
        }
    }
</script>
<style>

</style>
