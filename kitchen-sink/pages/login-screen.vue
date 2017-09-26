<template>
  <f7-page login-screen no-navbar>
    <f7-login-screen-title>登录</f7-login-screen-title>
    <f7-list form>
      <f7-list-item>
        <f7-label>用户</f7-label>
        <f7-input name="username" placeholder="用户"></f7-input>
      </f7-list-item>
      <f7-list-item>
        <f7-label>密码</f7-label>
        <f7-input name="password" type="password" placeholder="密码"></f7-input>
      </f7-list-item>
    </f7-list>
    <f7-list>
      <f7-list-button title="登录" back></f7-list-button>
      <f7-list-label>
        <p>点击登录关闭</p>
      </f7-list-label>
    </f7-list>
  </f7-page>
</template>
<script>
  export default {}
</script>