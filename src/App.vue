<template>
  <div id="app">
		<router-view></router-view>
		<main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import mainTabBar from 'components/mainTabBar/mainTabBar.vue'
export default {
  name: 'App',
	components:{
		mainTabBar
	}
}
</script>

<style>
  @import url("./assets/css/base.css");
</style>
