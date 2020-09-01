<template>
	<view class="container">
		<!-- left左侧列表 -->
		<view class="left">
			<!-- 循环遍历的 -->
			<view class="left_list activeList" >
				<label for="">施华蔻</label>
			</view>
			<view class="left_list" >
				<label for="">沙宣</label>
			</view>
			<view class="left_list" >
				<label for="">施华蔻</label>
			</view>
			<view class="left_list" >
				<label for="">欧莱雅</label>
			</view>
			<view class="left_list" >
				<label for="">施华蔻</label>
			</view>
			<view class="left_list" >
				<label for="">施华蔻</label>
			</view>
		</view>
		<!-- right右侧详细分类商品 -->
		<view class="right">
			<!-- 每一个小类 -->
			<view class="right_list">
				<!-- 商品 -->
				<view class="bottom">
					<view class="bottom_list">
						<!-- 每个最多显示6个 -->
						<view >
							<image src="/static/classify/11.jpg" alt="">
						</view>
						<view class="title">
							<span>商品</span>
						</view>
					</view>
				</view>
				
			</view>
		</view>
		
		
		
	</view>
</template>

<script></script>

<style>
	/* 导入外部的样式文件 */
	@import url("../../common/css/classify.css");
	
	/* 点击左侧导航，显示动态样式 */
	.activeList{
		border-left: 6rpx solid #f26b11;
		color: #f26b11;
	}
</style>
