<template>
  <div>
    <div
      class="a1"
      style="height:calc(100% - 100px - 200px);min-height: cacl(100vh - 100px - 200px) ;"
    >
      <div class="box logo"><img src="../html/imgs/imges/2b.png"></div>
      <div class="box1 login">
        <div class="login1">
          <div class="huiyuan"></div>
          <div class="hea"><div class="huiyuan-item" style="margin-left: 1px;">会员登陆</div>
            <input type="text" placeholder="会员账号/手机号" >
            <input type="password" placeholder="密码">
            <div class="hea"><div class="hea1" style="margin-left: 1px;"><div class="el-input"></div></div>
          <input type="text" placeholder="" >
           <div class="hea"></div>
           <div class="hea"></div>
           <div class="hea"></div>
        </div>
        </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
    *{
        margin: 0;
        padding: 0;
    }
.a1 {
  background-image: url(../html/imgs/imges/3b.jpg);

  background-repeat: no-repeat;
  background-size: cover;
  background-color: #f5f5f5;
}
.box {
  position: absolute;
  left: 10%;
  top: 15vh;
}
.box1 {
  position: absolute;
  width: 360px;
  left: 60%;
  top: 25vh;
}
.login1 {
  background: #fff;
  padding: 20px 40px;
}
.hea {
  margin-bottom: 22px;
}
.huiyuan-item {
  line-height: 40px;
  position: relative;
  font-size: 14px;
}
.hea1{
    
    line-height: 40px;
    position: relative;
    font-size: 14px;

}

.el-input {
    position: relative;
    font-size: 14px;
    display: inline-block;
    width: 100%;
}

</style>
