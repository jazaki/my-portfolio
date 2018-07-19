<template>
    <div class="header">
        <h2>
            {{ title }}
        </h2>
    </div>
</template>

<script>
export default {
    name: 'Header',
    props: {
        title: String
    }
}
</script>

<style scoped>
h2{
    color: #ccc;
}
</style>



