<style scoped>

.start-link {
    color: black;
}

#hero {
    margin-top: 150px;
}
#hero-title {
    text-align: center;
    font-family: 'Jacquarda Bastarda 9', sans-serif;
    font-size: 4rem;
}

#hero-start-btn {
    font-family: sans-serif;
    text-align: center;
    font-weight: 700;
    margin-top: 20px;
    padding: 20px 40px 20px 40px;
    background-color: rgb(138, 197, 138);
    border: none;
    border-radius: 4px;
}

    #hero-start-btn:hover {
        transform: translateY(-20px);
        transform: translateY(-20px);
        background-color: rgb(81, 126, 94);
        color: white;
    }


</style>

<template>
<section id="hero" class="hero">
    <div class="container">
        <h1 id="hero-title">Лучшие моды</h1>
        <button id="hero-start-btn"><a class="start-link" href="#">Начать</a></button>
    </div>
    </section>
</template>

<script setup lang="ts">
</script>