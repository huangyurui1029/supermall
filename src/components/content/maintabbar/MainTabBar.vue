<template>
  <tab-bar>
    <tab-bar-item path="/home">
      <img slot="item-icon" src="~assets/img/tabbar-icon/home.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar-icon/home_active.svg" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category">
      <img slot="item-icon" src="~assets/img/tabbar-icon/category.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar-icon/category_active.svg" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <img slot="item-icon" src="~assets/img/tabbar-icon/shopcart.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar-icon/shopcart_active.svg" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/mine">
      <img slot="item-icon" src="~assets/img/tabbar-icon/mine.svg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar-icon/mine_active.svg" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
    import TabBar from 'components/common/tabbar/TabBar'
    import TabBarItem from 'components/common/tabbar/TabBarItem'

    export default {
        name: "MainTabBar",
        components: {
            TabBar,TabBarItem
        }
    }
</script>

<style scoped>

</style>
