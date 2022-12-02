<template>
	<view class="content">
		<!-- 标题 +搜索框 -->
		<view >
			<view class="u-navbar u-navbar-fixed" >
				<!-- <view class="u-status-bar" ></view> -->
				<view class="u-navbar-inner" >
					<view class="u-back-wrap">
						<view class="u-navbar-title">{{title||''}}</view>
						<!-- u-icon-wrap u-back-text u-line-1 -->
					</view>
					<view 
					hover-class="hover-search" 
					class="search-box"
					>
					<!-- search-box u-flex u-row-center u-col-center u-m-r-30 -->
						<u-icon name="search" color="red" size="66rpx"></u-icon>
					</view>
				</view>
			</view>
			<view class="u-swiper">
				轮播图	
			</view>			
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '小程序demo'
			};
		},
		onLoad() {},
		methods: {},
	};
</script>

<style lang="scss">
	.u-navbar-inner{
		width: 100%;
		border: 1px solid;
		display: flex;
		justify-content: space-between;	
		.u-navbar-title{
			color: gray;
			padding: 14rpx 14rpx 14rpx 24rpx;
		}
		.search-box {
			width: 66rpx;
			height: 66rpx;
			background:#716d6d33;
			border-radius: 100%;
		}
	}
	

	
</style>
