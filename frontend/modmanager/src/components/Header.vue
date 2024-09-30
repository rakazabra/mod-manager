<script setup lang="ts">

</script>
<template>
<header id="header" class="header">
    <div class="container">
        <nav id="header-nav" class="header-nav">
            <div id="header-list" class="header-list">
                <li class="header-nav-" id="logo">LOGO</li>
                <li><ul class="nav-list">
                <li class="header-nav-item">Главная</li>
                <li class="header-nav-item">Моды</li>
                <li class="header-nav-item">Поддержка</li>
                <li class="header-nav-item">Аккаунт*</li>
            </ul></li>
            </div>
        </nav>
    </div>
</header>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Jacquarda+Bastarda+9&display=swap");

.container {
    width: 1200px;
    padding: 20px;
    margin: 0 auto;
}

#header-list {
    display: flex;
    gap: 50px;
    padding-top: 15px;
    padding-bottom: 5px;
    align-items: center;
}

.nav-list {
    display: flex;
    gap: 40px;
    margin-right: auto;
}

.header-nav-item {
    font-family: 'Jacquarda Bastarda 9', sans-serif;
    letter-spacing: 1.2;
}

.header-nav-item:hover,
.header-nav-item:focus {
    font-family: 'Jacquarda Bastarda', sans-serif;
    letter-spacing: 1.2;
    padding: 7px;
    background-color: rgb(63, 114, 63);
    color: white;
    transform: translateY(-10px);
	transform: translateY(-10px);
    border-radius: 4px;
    font-weight: 700;
}

#logo {
margin-right: 650px;
font-family: 'Jacquarda Bastarda', sans-serif;
}
</style>

