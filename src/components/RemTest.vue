<template>
  <div class="rem-test">
    <h1 class="title">测试postcss-px2rem工具</h1>
    <p class="text">rem是（font size of the root element），官方解释意思就是根据网页的根元素来设置字体大小，和em（font size of the
      element）的区别是，em是根据其父元素的字体大小来设置，而rem是根据网页的跟元素（html）来设置字体大小的。</p>
    <img class="logo" src="../assets/logo.png">
  </div>
</template>

<script type="text/ecmascript-6">
  export default {
    props: {},
    data() {
      return {}
    },
    methods: {}
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  .rem-test
    .title
      font-size: 18px
    .text
      font-size:16px
    .logo
      width: 100px
      height: 100px
</style>
