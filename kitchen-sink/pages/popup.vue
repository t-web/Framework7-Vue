<template>
  <f7-page tabbar-fixed>
    <f7-navbar back-link="Back" title="弹出层" sliding></f7-navbar>

    <p>
      <a href="#" data-popup=".popup-page" class="open-popup">打开弹出层 </a>
    </p>
    

    <!-- Popup -->
    <f7-popup class="popup-page" popup:open>
      <!-- Popup content goes here -->
      呜呜呜呜,测试内容
      <a href="#" data-popup=".popup-page" class="close-popup">关闭 </a>

    </f7-popup>

  </f7-page>
</template>
<script>



export default {

}

</script>