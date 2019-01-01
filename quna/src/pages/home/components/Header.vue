<template>
  <div class="header">
    <div class="header-left"><i class="iconfont">&#xe604;</i></div>
    <div class="header-input"><i class="iconfont">&#xe632;</i>输入城市/景点/游玩主题</div>
    <div class="header-right">城市<i class="iconfont">&#xe6aa;</i></div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .header
    display: flex
    line-height: 0.86rem;
    background-color: $bgColor;
    color: #fff;
    .header-left
      width: 0.64rem;
      float: left;
    .header-input
      flex: 1
      margin-top: .12rem
      margin-left: 0.2rem;
      height: 0.64rem
      line-height: 0.64rem
      background-color: #fff
      border-radius: 0.1rem
      padding-left: 0.15rem
      color: #ccc
      text-align: left
    .header-right
      width: 1.24rem;
      float: right;
      text-align: center;
</style>
