<template>
    <Head>
        <title>Sobre</title>
    </Head>
    <div>
        <h1>Estou na Página About</h1>
        <h2>Olá {{ name }}</h2>
        <h2>Estou no curso de {{ curso }}</h2>
        <menu-layout />
    </div>
</template>
<script>
    import {Link, Head} from '@inertiajs/vue3'
    import MenuLayout from '../Layouts/LayoutMenu.vue'
    export default {
        name: 'PageAbout',
        components:{
            Head,
            Link,
            MenuLayout
        },
        props:{
            name: String,
            curso: String
        }
    }
</script>
<style>

</style>
