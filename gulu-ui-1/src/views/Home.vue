<template>
    <div>
        <Topnav />
        <div class="banner">
            <h1>demoUI</h1>
            <h2>UI框架</h2>
            <p class="actions">
                <a>Github</a>
                <a>star</a>
            </p>
        </div>
    </div>
</template>

<script lang="ts">
    import Topnav from '../components/Topnav.vue'
    export default {
        components: { Topnav }
    }
</script>
<style lang="scss" scoped>
</style>