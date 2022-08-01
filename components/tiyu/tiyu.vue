<template>
	<view class="content">
		<view class="b1">
			1
		</view>
		<view class="b1">
			2
		</view>
		<view class="b1">
			3
		</view>
		<view class="b1">
			4
		</view>
	</view>
</template>

<script>
</script>

<style lang="scss">
	.content{
		display: flex;
		justify-content: space-evenly;
		align-items: center;
		flex-wrap: wrap;
		width: 100%;
		.b1{
			width: 45%;
			height: 200rpx;
			text-align: center;
			border: 1px solid #000;
			margin-top: 10rpx;
		}
	}
</style>