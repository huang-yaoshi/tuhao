<template>
    <div>
        <mt-header title="途濠云记录系统">
            <mt-button icon="more" slot="right"></mt-button>
        </mt-header>
        <img src="../assets/image/u26.svg" alt="" width="100%">
        <p class="title-center">推送</p>
        <div class="list-img">
            <p><img src="../assets/image/u24.png" alt=""></p>
            <p><img src="../assets/image/u22.png" alt=""></p>
        </div>
        <div class="list-img">
            <p><img src="../assets/image/u23.png" alt=""></p>
            <p><img src="../assets/image/u20.png" alt=""></p>
        </div>
        <div class="list-img">
            <p><img src="../assets/image/u21.png" alt=""></p>
            <p><img src="../assets/image/u25.png" alt=""></p>
        </div>
    </div>
</template>

<style scoped>
.title-center{
    text-align: center;
    padding: 10px 0;
    border: 1px solid #666
}
.list-img{
    display: flex;
    flex-direction: row;
}
.list-img p {
   width: 50%;
   padding: 10px 50px;
}
.list-img p img{
   width: 100%;
}
</style>

