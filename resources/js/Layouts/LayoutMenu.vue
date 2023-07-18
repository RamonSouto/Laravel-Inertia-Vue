<template>
    <div class="mt-4">
        <Link :href="route('home')" :class="{'font-bold': $page.url === '/home'}">Home</Link> -
        <Link :href="route('about')" :class="{'font-bold': $page.url === '/about'}">About</Link>
    </div>
</template>
<script>
    import { Link } from '@inertiajs/vue3'
    export default {
        name: 'LayoutMenu',

        components:{
            Link
        }
    }
</script>
<style>

</style>
