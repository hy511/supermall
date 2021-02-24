<template>
  <tab-bar>
      <tab-bar-item link="/home" activeColor="blue">
      <template v-slot:item-icon>
        <img src="~assets/img/tabbar/home.svg" alt="" />
      </template>
      <template v-slot:item-icon-active>
        <img src="~assets/img/tabbar/home_active.svg" alt="" />
      </template>
      <template v-slot:item-text>
        <div>首页</div>
      </template>
      </tab-bar-item>

    </tab-bar>
</template>

<script>
  import TabBar from "components/common/tabbar/TabBar";
  import TabBarItem from "components/common/tabbar/TabBarItem";
  export default {
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style>

</style>