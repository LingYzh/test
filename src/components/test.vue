<template>
    <div>
        <h1>9999 {{t_data}}</h1>
    </div>
</template>

<script>
    export default {
        name: 'test',
        props: ['t_data'],
    }
</script>

<style scoped>
    h1{
        color: #6cf;
    }
</style>