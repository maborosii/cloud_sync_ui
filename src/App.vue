<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

// 用于百度统计
<!-- <script>
var _hmt = _hmt || [];
(function () {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?1d2d61263f13e4b288c8da19ad3ff56d";
  var s = document.getElementsByTagName("script")[0];
  s.parentNode.insertBefore(hm, s);
})();
</script> -->

<style lang="scss">
.el-dialog__wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
