<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe667;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe62c;</span>
      输入城市/游玩/主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont arrow-icon">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'header'
}
</script>

<style lang="stylus" scoped>
  @import "~styles/varibles.styl"
  .header
    line-height: .86rem
    display: flex
    background-color: $bgColor
    color: #fff
    .header-left
       width: .64rem
       float: left
       .back-icon
         text-align: center
         font-size: .4rem
    .header-input
       flex: 1
       height: .64rem
       line-height: .64rem
       margin-top: .12rem
       margin-left: .2rem
       padding-left: .2rem
       background-color: #fff
       border-radius: .1rem
       color: #ccc
    .header-right
       width: 1.24rem
       float: right
       text-align: center
       .arrow-icon
         margin-left: -.04rem
         font-size: .24rem
</style>
