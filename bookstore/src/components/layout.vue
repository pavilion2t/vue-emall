<template>
  <div>
      <div class="app-head">
          <div class="app-head-inner">
              <img src="../assets/logo.png" id="logo">
              <div class="head-nav">
                  <ul class="nav-list">
                    <li>登录</li>
                    <li>注册</li>
                    <li>关于</li>
                  </ul>
             </div>
          </div>
      </div>
      <div class="app-content">content</div>
      <div class="app-footer">
          <p>@ 2018 misstakau MIT </p>
      </div>
  </div>
</template>

<script>
export default {
}
</script>

<style>
.app-head{
    background-color: #363636;
    height: 90px;
}
.app-head-inner{
    width: 1200px;
    margin: 0 auto;
}
.head-nav{
    float: right;
    color: aliceblue;
}
.head-nav li{
    float: left;
    padding-right: 20px;
}
#logo{
    width: 80px;
    height: 80px;
}
</style>
