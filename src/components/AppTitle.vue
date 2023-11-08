<template>
    <h1>{{ title }}</h1>
</template>

<script>
export default {
    name: "AppTitle",
    data() {
        return {
            title: "la mia prima app con Vite!"
        }
    }
}
</script>

<style lang="css" scoped>
h1 {
    font-size: 2em;
    font-weight: 800;
    color: black;
    padding: 30px;
    text-align: center;
    text-transform: capitalize;
}
</style>