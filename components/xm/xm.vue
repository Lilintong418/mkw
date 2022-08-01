<template>
	<view class="content">
		<view class="left">
			<image src="https://m.imooc.com/static/wap/static/common/img/logo2.png"></image>
		</view>
		<view class="zhong">
			<p>C语言系统化精讲 重塑编程思想 打造坚实的开发基础</p>
			<p>
				<span>进阶</span>
				<span>·</span>
				<span>1598</span>
			</p>
		</view>
		<view class="right">
			<span>￥299</span>
		</view>
	</view>
</template>

<script>
</script>

<style lang="scss">
	.content{
		display: flex;
		padding: 0 35rpx 0 35rpx;
		align-items: center;
		margin-bottom: 20rpx;
		.left{
			image{
				width: 200rpx;
				height: 100rpx;
			}
		}
		.zhong{
			overflow: hidden;
			text-overflow: ellipsis;
			display: -webkit-box;
			-webkit-line-clamp: 2;
			-webkit-box-orient: vertical;
			margin: 0 20rpx;
		}
		.right{
			text-align: center;
		}
	}
</style>
