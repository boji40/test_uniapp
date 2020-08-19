<template>
	<view class="content">
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
		<view class="textCont">
			<test class="title">Croissant With BlueBerry</test>
			<view>
				<text style="font-size:14px">xxxx</text>
			</view>
			<text class="price">13.5</text>
			<view class="desc">
				<view>描述</view>
			</view>
		</view>
		<view class="img">
			<image src="../../static/img/blueBerry.jpg"></image>
			<image src="../../static/img/blueBerry.jpg"></image>
			<image src="../../static/img/blueBerry.jpg"></image>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	.swiper-container {
		width: 100%;
	}
	.title{
		font-weight: normal;
		font-size: 19px;
	}
	.price{
		font-size:16px;
		color:#C69C6D;
	}
	.desc {
		 text-align: left;  
	}
</style>
