<template>
  <div id="app">
    <ul class="menulist">
      <li class="menulist-item">首页</li>
      <li class="menulist-item">分类</li>
      <li class="menulist-item">购物车</li>
      <li class="menulist-item">我的</li>
    </ul>
  </div>
</template>

<style lang="scss">

.menulist{
  display: flex;
  position: fixed;
  bottom:0;
  width: 100%;
  background: gray;
  
  &-item{
    flex-grow: 1;
    text-align: center;
    padding-bottom: 0.5rem;
}
}
</style>
