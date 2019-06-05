<template>
    <div>
        <mt-header title="我的项目">
            <router-link to="/" slot="left">
                <mt-button icon="back"></mt-button>
            </router-link>
            <mt-button icon="more" slot="right"></mt-button>
        </mt-header>
        <mt-search
        v-model="value"
        cancel-text="取消"
        placeholder="搜索">
        </mt-search>
        <footer>
            <p>主办</p>
            <p>协办</p>
        </footer>
    </div>
</template>
<script>
export default {
    name:'Myproject',
    data(){
        return{
            value:'',
            selected:'1'
        }
    }
}
</script>
<style scoped>
footer{
    position: fixed;
    bottom: 0;
}
</style>


