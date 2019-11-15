<template>
  <div id="app">
    <router-view>
    </router-view>
    <ul class="menulist">
     <li class="menulist-item"><router-link to="/">首页</router-link></li>
     <li class="menulist-item"><router-link to="/category">分类</router-link></li>
     <li class="menulist-item"><router-link to="/cart">购物车</router-link></li>
     <li class="menulist-item"><router-link to="/mine">我的</router-link></li>
    </ul>
  </div>
</template>

<style lang="scss">
.menulist{
  position: fixed;
  bottom:0;
  width: 100%;
  background: gray;
  display: flex;
  width: 100%;
  &-item{
      flex: 1;  
      text-align: center;
      padding-top: 0.5rem;
      
    }
    
    
  
  }
  

</style>
