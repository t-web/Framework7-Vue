<template>
  <f7-page tabbar-fixed>
    <f7-navbar back-link="Back" title="弹出登录" sliding></f7-navbar>

    <p>
      <a href="#" data-popup=".popup-login" class="open-popup">登录 </a>
    </p>
    

    <!-- Popup
    <f7-popup class="popup-page" popup:open>
   
      呜呜呜呜,测试内容
      <a href="#" data-popup=".popup-page" class="close-popup">关闭 </a>

    </f7-popup> -->



<!-- Login Screen -->
<f7-login-screen class="popup-login">
  <!-- Login Screen content goes here -->

 <f7-view>
    <f7-pages>
      <f7-page login-screen>
        <f7-login-screen-title>登录</f7-login-screen-title>
        <f7-list form>
          <f7-list-item>
            <f7-label>Username</f7-label>
            <f7-input name="username" placeholder="Username"></f7-input>
          </f7-list-item>
          <f7-list-item>
            <f7-label>Password</f7-label>
            <f7-input name="password" type="password" placeholder="Password"></f7-input>
          </f7-list-item>
        </f7-list>
        <f7-list>
          <f7-list-button title="登录" close-login-screen></f7-list-button>
          <f7-list-label>
            <p>点击登录关闭</p> 
          </f7-list-label>
        </f7-list>
      </f7-page>
    </f7-pages>
  </f7-view>


      


</f7-login-screen>
  </f7-page>
</template>
<script>



export default {

}

</script>