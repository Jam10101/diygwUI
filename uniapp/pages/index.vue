<template>
	<view class="container">
		<image src="https://libs.diygw.com/upload/2022/02/16/5518a03b-d8e2-4873-b9cb-489a11ca1dbf/1jpg" class="response diygw-col-24" mode="widthFix"></image>
		<view class="flex diygw-col-24">
			<diy-noticebar class="flex1 diy-notice-bar" color="#07c160" bgColor="#fff" leftIcon="diy-icon-notification">
				<!-- #ifndef VUE3 -->
				<block slot="content">
					<text class="diy-notice-item"> 本应用所有演示页面都是DIY可视化一键生成，无需要编写任何一行代码 </text>
				</block>
				<!-- #endif -->
				<!-- #ifdef VUE3 -->
				<block v-slot:content>
					<text class="diy-notice-item"> 本应用所有演示页面都是DIY可视化一键生成，无需要编写任何一行代码 </text>
				</block>
				<!-- #endif -->
			</diy-noticebar>
		</view>
		<view class="flex diygw-col-24 audio-clz">
			<diy-audio class="flex-sub" author="DIYGW可视化音频组件" music="http://cdn.diygw.com/1.mp3" avatar-type="icon" title="♪" icon="diy-icon-musicfill" background-clazz="green" size-clz="" active-color="#07c160" is-silder is-title autoplay poster="/static/grid7.png"></diy-audio>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-list">
				<view @tap="navigateTo" data-type="page" data-url="/pages/grid" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-mauve">
					<view class="diygw-avatar diy-icon-apps"> </view>
					<view class="content">
						<view class="title"> 九宫格 </view>
						<view class="text-sm remark"> Flex </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/list" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-pink">
					<view class="diygw-avatar diy-icon-sort"> </view>
					<view class="content">
						<view class="title"> 列表 </view>
						<view class="text-sm remark"> List </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/forms" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-red">
					<view class="diygw-avatar diy-icon-form"> </view>
					<view class="content">
						<view class="title"> 表单 </view>
						<view class="text-sm remark"> Form </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/swiper" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-gradual-orange">
					<view class="diygw-avatar diy-icon-album"> </view>
					<view class="content">
						<view class="title"> 轮播 </view>
						<view class="text-sm remark"> Swiper </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/cubes" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-purple">
					<view class="diygw-avatar diy-icon-cascades"> </view>
					<view class="content">
						<view class="title"> 魔方图片 </view>
						<view class="text-sm remark"> Title </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/steps" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-gradual-purple">
					<view class="diygw-avatar diy-icon-more"> </view>
					<view class="content">
						<view class="title"> 步骤条 </view>
						<view class="text-sm remark"> Step </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/timeline" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-gradual-green">
					<view class="diygw-avatar diy-icon-home"> </view>
					<view class="content">
						<view class="title"> 时间轴 </view>
						<view class="text-sm remark"> Timelime </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/title" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-purple">
					<view class="diygw-avatar diy-icon-clothes"> </view>
					<view class="content">
						<view class="title"> 标题 </view>
						<view class="text-sm remark"> Title </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/avatar" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-orange">
					<view class="diygw-avatar diy-icon-emoji"> </view>
					<view class="content">
						<view class="title"> 图标 </view>
						<view class="text-sm remark"> Icon </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/button" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-olive">
					<view class="diygw-avatar diy-icon-btn"> </view>
					<view class="content">
						<view class="title"> 按钮 </view>
						<view class="text-sm remark"> Button </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/tag" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-cyan">
					<view class="diygw-avatar diy-icon-tag"> </view>
					<view class="content">
						<view class="title"> 标签 </view>
						<view class="text-sm remark"> Tag </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/image" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-gradual-red">
					<view class="diygw-avatar diy-icon-picfill"> </view>
					<view class="content">
						<view class="title"> 图片 </view>
						<view class="text-sm remark"> Image </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/buttons" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-blue">
					<view class="diygw-avatar diy-icon-colorlens"> </view>
					<view class="content">
						<view class="title"> 底部按钮组 </view>
						<view class="text-sm remark"> Buttons </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/layout" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-green">
					<view class="diygw-avatar diy-icon-circle"> </view>
					<view class="content">
						<view class="title"> 布局 </view>
						<view class="text-sm remark"> Layout </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/notice" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-gradual-green">
					<view class="diygw-avatar diy-icon-notification"> </view>
					<view class="content">
						<view class="title"> 通知栏 </view>
						<view class="text-sm remark"> Notice </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/absolute" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-gradual-pink">
					<view class="diygw-avatar diy-icon-form"> </view>
					<view class="content">
						<view class="title"> 绝对布局 </view>
						<view class="text-sm remark"> Absolute </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/progress" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-purple">
					<view class="diygw-avatar diy-icon-clothes"> </view>
					<view class="content">
						<view class="title"> 进度条 </view>
						<view class="text-sm remark"> Progress </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/rate" style="" class="diygw-item col-50 flex-direction-row-reverse solid-bottom diygw-card diygw-shadow list-item-clz bg-blue">
					<view class="diygw-avatar diy-icon-clothes"> </view>
					<view class="content">
						<view class="title"> 星级评分 </view>
						<view class="text-sm remark"> Rate </view>
					</view>
				</view>
			</view>
		</view>
		<view class="clearfix"></view>
	</view>
</template>

<script>
	//create by: 邓志锋 <280160522@qq.com> <https://www.diygw.com> DIYGW可视化设计一键生成源码
	export default {
		data() {
			return {};
		},
		onShareAppMessage: function () {},
		onLoad(option) {
			this.setCurrentPage(this);
			if (option) {
				this.setData({
					globalOption: option
				});
			}
		},
		mounted() {
			this.init();
		},
		methods: {
			async init() {}
		}
	};
</script>

<style lang="scss" scoped>
	.audio-clz {
		margin-left: 5px;
		width: calc(100% - 5px - 5px) !important;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.container {
		padding-bottom: 80px;
	}
</style>
