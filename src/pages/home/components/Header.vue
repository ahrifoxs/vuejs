<template>
   <div>
        <div class="header">
            <div class="header-left"><div class="iconfont">&#xe645;</div></div>
            <div class="header-input"><span class="iconfont">&#xe6c6;</span>输入城市/主题/游玩风景</div>
            <div class="header-right">城市<span class="iconfont">&#xe6aa;</span></div>
            </div>     
    </div> 
   

</template>
<script>
    export default{
        name:'header'
    }
</script>
// scoped只对本组件的class起作用
<style lang="stylus" scoped>
@import '~styles/varibles.styl'
    .header
      display:flex
      line-height:$headerHeight
      background:$bgColor
      color:#fff
      .header-left
        width:.64rem
        float:left
        .back-icon
          text-align:center
          font-size:.4rem
      .header-input
        flex:1
        height:.64rem
        line-height:.64rem
        margin-top:.12rem
        margin-left:.2rem
        padding-left:.2rem
        background:#fff
        border-radius:.1rem
        color:#ccc
      .header-right
        width:1.24rem
        float:right
        text-align:center
        color:#fff
        .arrow-icon
            margin-left:-.04rem
            font-size:.24rem
</style>