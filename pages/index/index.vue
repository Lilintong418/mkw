<template>
	<view class="content">
		<view class="head">
			<image class="logo" src="https://m.imooc.com/static/wap/static/common/img/logo2.png"></image>
			<span>
				<a href="#">下载      </a>
				<a href="#"> | </a>
				<a href="#">     登录</a>
			</span>
		</view>
		<u-sticky offset-top="0" class="top">
			<ul>
				<a>首页</a>
				<a>免费课</a>
				<a>实战课</a>
				<a>体系课</a>
			</ul>
			<ul>
				<a>专栏</a>
				<a>手记</a>
				<a>慕课教程</a>
			</ul>
		</u-sticky>
		<view class="shizhan">
			<view class="tt">
				<span>实战推荐</span>
				<span>查看更多 ></span>
			</view>
			<xm v-for="index in 10"></xm>
		</view>
		<view class="tiyu">
			<view class="t1">
				<span>体育</span>
				<span>查看更多 ></span>
			</view>
			<tiyu></tiyu>
		</view>
		<zujian></zujian>
	</view>
</template>

<script>
	import xm from "@/components/xm/xm.vue"    //列表
	import zujian from "@/components/zujian/zujian.vue"   //轮播图
	import tiyu from "@/components/tiyu/tiyu.vue"     //体育四小块
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		components:{
			xm,
			zujian,
			tiyu
		},
		methods: {

		}
	}
</script>

<style lang="scss">
	.content{
		.head{
			display: flex;
			justify-content: space-between;
			.logo{
				width: 200rpx;
				height: 80rpx;
				margin: 15rpx 0 0 30rpx;
			}
			span{
				background-color: rgba(242,13,13,.06);
				margin: 30rpx 30rpx 0 0;
				border-radius: 35rpx;
				a{
					color: #f01414;
					text-decoration: none;
					margin: 5rpx;
				}
			}
		}
		.top{
			ul{
				display: flex;
				justify-content: space-evenly;
				a{
					color: #71777d;
				}
			}
		}
		.shizhan{
			.tt{
				display: flex;
				justify-content: space-between;
				margin: 0 35rpx 12rpx;
				
			}
			
		}
		.tiyu{
			.t1{
				display: flex;
				justify-content: space-between;
				margin: 0 35rpx;
			}
		}
	}
</style>
