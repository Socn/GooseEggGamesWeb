<script lang="ts">
</script>

<template>
    <head>
        <title>鹅蛋工作室 | GooseEggGames</title>
    </head>
    <body>
        <header>
            <div class="logo"></div>
            <div class="actions">
                <div class="actions-item"></div>
                <div class="actions-item"></div>
                <div class="actions-item"></div>
            </div>
        </header>
    </body>
</template>

<style lang="scss">
header{
    background-color: rgb(233,233,233);
    height: 80px;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 10px;
    box-sizing: border-box;
    position: fixed;
    top: 0;
    width: 100%;
    .logo{
        width: 150px;
        height: 50px;
        background-color: rgb(200,200,200);
        border-radius: 10px;
        position: relative;
    }
    .actions{
        width: auto;
        height: 50px;
        padding: 10px;
        box-sizing: border-box;
        background-color: rgb(200,200,200);
        border-radius: 10px;
        position: relative;
        right: 0;
        margin-left: auto;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        .actions-item{
            height: 30px;
            width: 80px;
            border-radius: 10px;
            background-color: rgb(180,180,180);
            flex-basis: 75px;
        }
    }
}
</style>