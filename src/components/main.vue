<script lang="ts">
</script>

<template>
    <head>
        <title>鹅蛋工作室 | GooseEggGames</title>
    </head>
    <header>
        <div class="logo"></div>
        <div class="actions">
            <div class="actions-item"></div>
            <div class="actions-item"></div>
            <div class="actions-item"></div>
        </div>
    </header>
    <div id="body">
        <content>

        </content>

        <footer>
            Copyright © 2023 Goose Egg Studio
        </footer>
    </div>
</template>

<style lang="scss">
header{
    background-color: rgba(233,233,233,0.6);
    backdrop-filter: blur(20px);
    height: 80px;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 10px;
    box-sizing: border-box;
    position: fixed;
    top: 0;
    width: 100vw;
    z-index: 1000;
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

#body{
    height: 100vh;
    overflow-y: scroll;
    
}
#body::-webkit-scrollbar{
    width: 14px;
    border-radius: 8px;
}
#body::-webkit-scrollbar-thumb {
    background: rgb(150,150,150); // 滑块颜色
    border-radius: 8px ; // 滑块圆角
    border: solid rgb(255,255,255) 3px;
}

#body::-webkit-scrollbar-thumb:hover {
    background: rgb(100,100,100); // 鼠标移入滑块变红
}

#body::-webkit-scrollbar-track {
    border-radius: 10px; // 轨道圆角
    background-color: rgb(255,255,255) // 轨道颜色 
}
content{
    position: relative;
    display: block;
    width: 100%;
    height: 200vh;
}

footer{
    position: relative;
    bottom: 0;
    height: 80px;
    background-color: rgb(233,233,233);
    vertical-align: middle;
    line-height: 80px;
    text-align: center;

}
</style>