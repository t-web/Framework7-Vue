<template>
  <f7-page tabbar-fixed>
    <f7-navbar back-link="Back" title="默认打开登录" sliding></f7-navbar>

    <p>
      <a href="#" data-popup=".popup-login" class="open-popup">登录 </a>

       <a href="#" data-popup=".popup-login" class="open-popup">登录 </a>

       <p v-if="seen">Now you see me</p>
    </p>

    <!-- Login Screen -->
    <f7-login-screen class="popup-login" v-if="seen" opened>
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
  data: function() {
    return {
      login: '',
      seen:true,
      opened:false

    }

  },
  mounted(){
  console.log('swipeout deleted');
  }


}

</script>