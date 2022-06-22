<template>
    <div>
        <router-link :to='name'>{{name}}</router-link>
    </div>
</template>

<script>
    export default {
        props:['name']
    }
</script>

<style lang="scss" scoped>

</style>