<template>
    <div class="header">
        <div class="header-left">返回</div>
        <div class="header-input">内容</div>
        <div class="header-right">城市</div>
    </div>
</template>

<script>
export default {
    name: 'HomeTop'
}
</script>
<style lang="stylus" scoped>
    .header
        height .86rem
        display flex
        background #00b4d4
    .header-left
        width .64rem
        float left
    .header-input
        flex 1
    .header-right
        width 1.24rem
        float left

</style>

