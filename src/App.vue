<template>
  <div id="app">
    <!-- <img src="./assets/img/piao.jpeg">  -->
    	<!-- 当前路由显示的地址的内容 -->
    <router-view/>
    
  </div>
</template>

<script>
export default {
  name: 'App'
}

</script>

<style>
body {
  margin: 0
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
