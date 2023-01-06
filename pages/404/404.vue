<template>
	<view>
		<h1>当前页面不存在！！！</h1>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onShow() {
			let timer = setTimeout(()=>{
				uni.navigateTo({
					url:'/pages/index/index'
				})
			},2000)
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
