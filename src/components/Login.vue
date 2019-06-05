<template>
  <div class="login">
    <div class="loginform">
      <img src="../assets/image/u7.png" alt="" class="logo-img">
      <h3>途豪云记录系统</h3>
      <mt-field label="用户名" placeholder="请输入用户名" v-model="username"></mt-field>
      <mt-field label="密码" placeholder="请输入密码" type="password" v-model="password"></mt-field>
      <mt-button type="primary" class="login-button" size="large">登录</mt-button>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
     username:'',
     password:''
    }
  }
}
</script>
<style scoped>
  .login{
    display: flex;
    align-items: center;
    flex-direction: column;
    padding: 20vh 0  0  0
  }
  .loginform{
    display: flex;
    align-items: center;
    flex-direction: column;
    width: 80%;
  }
  .login-button{
    margin-top: 30px
  }
  .logo-img{
    display: block;
    width: 100px;
    margin-bottom: 20px
  }
  h3{
    margin: 15px 0;
    color: #26a2ff
  }
</style>


