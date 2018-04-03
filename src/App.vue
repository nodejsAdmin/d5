<template>
  <div id="app">
  	<div id="doudou"></div>
    <div id="nav">
    	<img src="http://ccdn.goodq.top/caches/7f72634bb4b7fbd4cacee150ae5ac686/aHR0cDovLzVhNWM1YzVmNjU5NmQudDczLnFpZmVpeWUuY29tL3FmeS1jb250ZW50L3VwbG9hZHMvMjAxOC8wMS8xMzNkM2NmMThmYzMxOGQwNTE5MWRjNzIwOTI3ZmFhNS5wbmc_p_p100_p_3D.png"/>
      <router-link to="/">首页</router-link>
      <router-link to="/new/1">全新楼盘</router-link>
      <router-link to="/new/2">二手楼盘</router-link>
      <router-link to="/new/3">全新商铺</router-link>
      <router-link to="/dongt">楼市动态</router-link>
      <router-link to="/news">联系我们</router-link>
      <router-link to="/news"><img src="img/dh.jpg" alt="" />008-6666 6666<span>咨询电话</span></router-link>
    </div>
    <div id="clear">
    	<img src="./assets/0.jpg" alt="" />
    	<img src="./assets/2.jpg" alt="" />
    	<img src="./assets/3.jpg" alt="" />
    </div>
    <div id="content">
    	<div id="left">
    		
    	</div>
    </div>
    <router-view/>
  </div>
</template>

<style>
	*{
		margin:0;
		padding:0;
		list-style: none;
  	text-decoration: none;
	}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
}
#doudou{
	width: 100%;
	height: 64px;
	margin:0 auto;
	background: black;
}
#nav {
	width: 90%;
	height: 100px;
	margin:0 auto;
 line-height: 100px;
}
#nav a:last-of-type{
	color: black;
	float: right;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
  line-height:4;
  padding: 15px;
}
#nav span{
	width: 86px;
	height: 31px;
	line-height: 31px;;
	background: blue;
	color: white;
	float: right;
	margin-top: 15px;
	border-radius: 5px;
}
#nav img:nth-child(1){
	float: left;
	margin-top: 20px;
}
#nav span{
float: right;
}
#clear{
	width: 90%;
	height: 600px;	
	background: red;
	margin: 0 auto;
	overflow: hidden;
}
#clear img{
	width: 100%;
	height: 600px;
	float: left;
}
</style>
<script type="text/javascript">
	export default{
		
	}
</script>