<template>
  <div class="header-v">
      <div class="login">
          <span>{{login}}</span>
          <span>/</span>
          <span>{{logup}}</span>
      </div>
      <div class="input-v">
          <input class="input-1" type="text">
      </div>
  </div>
</template>
<script>
    export default{
        data(){
            return {
                login:"登录",
                logup:"注册"
            }
        }
    }
</script>
<style>
.header-v{
    width: 100%;
    height: 3.75rem;
    background-color: rgb(187, 187, 187);
}
.header-v .login{
    height: 3.75rem;
    float: left;
    line-height: 3.75rem;
    margin-left: .625rem;
}
.header-v .input-v{
    height: 3.75rem;
    float: right;
    line-height: 3.75rem;
}
.header-v .input-v .input-1{
    height: 1.5625rem;
    width: 12.5rem;
    margin-right: 1.25rem;
    border-radius: .625rem;
    border: none;
}
</style>


