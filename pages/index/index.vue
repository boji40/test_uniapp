<template>
	<view class="content">
		<view class="topbar">
			<image src="https://static.21cake.com/themes/wap/img/logo.png" class="title-logo" alt="21cake logo"/>
		</view>
		<view class="fill"></view>
		<view class="swiper-container">
			<swiper :indicator-dots="true" :autoplay="true" :interval="2000">
				<swiper-item>
					<view class="swiper-item">
						<image src="../../static/img/newCake.jpg"></image>
					</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item">
						<image src="../../static/img/newCake.jpg"></image>
					</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item">
						<image src="../../static/img/newCake.jpg"></image>
					</view>
				</swiper-item>
			</swiper>
		</view>
		<view class="uni-flex uni-row">
			<view class="flex-item">新客满298元赠送切块蛋糕</view>
			<view class="flex-item" style="margin: 0 15px;">满100包邮</view>
			<view class="flex-item">全程冷链配送</view>
		</view>
		<view class="uni-flex uni-row">
			<view class="flex-item">
				<image src="../../static/img/cake.png"></image>
				蛋糕
			</view>
			<view class="flex-item">
				<image src="../../static/img/bread.png"></image>
				面包
			</view>
			<view class="flex-item">
				<image src="../../static/img/tea.png"></image>
				下午茶
			</view>
			<view class="flex-item">
				<image src="../../static/img/company.png"></image>
				企业专区
			</view>
		</view>
		<view class="goods">
			<view class="list">
				<view class="cover">
					 <image src="../../static/img/newCake.jpg"></image> 
				</view>
				<view class="text">
					<view class="cart">
					</view>
					<view>
						<text class="name">彼尔德</text>
						<text class="price">198</text>
						<text class="size">元45g</text>
					</view>
					<view class="des">
						<text>鼠年限定xxx</text>
					</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		components: {},
		onLoad() {
			
		},
		onShareAppMessage() {
			console.log('用户进行分享')
			
		},
		methods: {

		}
	}
</script>

<style scoped>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	.content .topbar {
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		z-index: 1000;
		background: #fff;
		height: 70rpx;
		box-shadow: 0px 2px 4px 0px rgba(0,0,0,0.10);
		text-align: center;
	}
	.content .topbar .title-logo {
		width: 28px;
		height: 28px;
	}
	.fill {
		width: 100%;
		height: 72rpx;
	}
	.swiper-container {
		width: 100%;
	}
	.flex-item {
		text-align: center;
	}
	.flex-item image {
		width: 30px;
		height: 30px;
		display: block;
		padding: 5px 15px;
	}
	.goods {
		width: 90%;
		border-top:1px solid #B2B2B2 ;
		margin-top:20rpx;
	}
	.goods .list{
		margin: 50rpx 0;
		box-shadow: 0 4px 4px 0 #BBB;
		border-radius: 4px;
	}
	.cover image {
		width: 100%;
	}
	.text{
		padding: 0px 0 0 10px;
	}
	.text .cart {
		width: 60rpx;
		height: 60rpx;
		float: right;
		margin-top: 20rpx;
		margin-right: 20rpx;
		background: url(https://static.21cake.com/themes/wap/img/new-home-icon.png) no-repeat;
		background-position: -90rpx -10rpx;
		background-size: 160rpx auto;
		border-radius: 50%;
	}
	.name{
		font-weight: bold;
		font-size:15px;
		color:#322418;
		
	}
	.price{
		color:#C69C6D;
		margin-left: 10px;
	}
	.size{
		color:#b2b2b2;
	}
	.des{
		color: #442818;
	
	}
</style>
