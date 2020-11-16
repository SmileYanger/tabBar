<template>
  <tab-bar>
      <tab-bar-item path='/home' activeColor="#1296db">
        <img src="../../assets/images/tabbar/home.png" alt="" slot="item-icon" />
        <img src="../../assets/images/tabbar/home-active.png" alt="" slot="item-icon-active" />
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path = '/cart' activeColor="#1296db">
        <img src="../../assets/images/tabbar/cart.png" alt="" slot="item-icon"/>
        <img src="../../assets/images/tabbar/cart-active.png" alt="" slot="item-icon-active" />
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path='/category' activeColor="#1296db">
        <img src="../../assets/images/tabbar/category.png" alt="" slot="item-icon"/>
        <img src="../../assets/images/tabbar/category-active.png" alt="" slot="item-icon-active" />
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path='/profile' activeColor="#1296db">
        <img src="../../assets/images/tabbar/profile.png" alt="" slot="item-icon" />
        <img src="../../assets/images/tabbar/profile-active.png" alt="" slot="item-icon-active" />
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>

<script>
import TabBar from './TabBar.vue';
import TabBarItem from "./TabBarItem.vue";
export default {
    name: 'TabBarIndex',
    components: {
    TabBar,
    TabBarItem,
  },
}
</script>

<style>

</style>