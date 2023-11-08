<template>
    <div id="hero">
        <h2>{{ titleHero }}</h2>
    </div>
</template>

<script>
export default {
    name: "AppHero",
    data() {
        return {
            titleHero: "Una grande e grossa sezione hero"
        }
    }
}
</script>

<style lang="css" scoped>
/* hero section */
#hero {
    height: 80vh;
    background-image: url(/images/hero.jpg);
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
}

/* hero title */
h2 {
    font-size: 6em;
    color: rgb(255, 255, 255);
}
</style>