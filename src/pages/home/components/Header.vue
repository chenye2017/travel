<template>
    <div class="header">
        <div class="header-left">
            <span class="iconfont back-icon">&#xe624;</span>
        </div>
        <div class="header-input">
            <span class="iconfont search-icon">&#xe632;</span>
        </div>
        <div class="header-right">
            城市<span class="iconfont arrow-icon">&#xe62d;</span>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>
@import '~styles/varibles.styl';
.header
    display: flex
    line-height: .86rem
    background: $bgColor
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
        margin-top: .12rem
        margin-left: .2rem
        background: #fff
        border-radius: .1rem
        padding-left: .2rem
    .header-right
        width: 1.24rem
        float: right
        text-align: center
        .arrow-icon
            margin-left: -.04rem
            font-size: .24rem
</style>
