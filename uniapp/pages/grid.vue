<template>
	<view class="container">
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-3">
				<view @tap="navigateTo" data-type="phone" data-phone="15913132246" class="diygw-grid-item">
					<view class="diygw-grid-inner grid10-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon2/icon2_gh.png"></image>
							<view class="diygw-tag badge empty grid10-badge-0 red"></view>
						</view>
						<view class="diygw-grid-title"> 点击打电话 </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="copy" data-copy="https://www.diygw.com" data-tip="" class="diygw-grid-item">
					<view class="diygw-grid-inner grid10-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon2/icon2_lj.png"></image>
						</view>
						<view class="diygw-grid-title"> 点击复制 </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="page" data-url="/pages/page/page" class="diygw-grid-item">
					<view class="diygw-grid-inner grid10-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon2/icon2_gd.png"></image>
						</view>
						<view class="diygw-grid-title"> 更多 </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="copy" data-copy="15913132246" data-tip="复制成功，前往微信查找" class="diygw-grid-item">
					<view class="diygw-grid-inner grid10-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon2/icon2_weixin.png"></image>
						</view>
						<view class="diygw-grid-title"> 微信 </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="copy" data-copy="luckyzf332" data-tip="复制成功，前往支付宝查找" class="diygw-grid-item">
					<view class="diygw-grid-inner grid10-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon2/icon2_zfb.png"></image>
						</view>
						<view class="diygw-grid-title"> 支付宝 </view>
					</view>
				</view>
				<view @tap="navigateTo" data-type="copy" data-copy="280160522" data-tip="复制成功，前往QQ查找" class="diygw-grid-item">
					<view class="diygw-grid-inner grid10-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon2/icon2_QQ.png"></image>
						</view>
						<view class="diygw-grid-title"> QQ </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-3">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_ht.png"></image>
							<view class="diygw-tag badge red"> 10 </view>
						</view>
						<view class="diygw-grid-title"> 话题 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_jb.png"></image>
							<view class="diygw-tag badge red"> 2 </view>
						</view>
						<view class="diygw-grid-title"> 证书 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_kf.png"></image>
						</view>
						<view class="diygw-grid-title"> 聊聊 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_pxb.png"></image>
						</view>
						<view class="diygw-grid-title"> 荣誉 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_dz.png"></image>
						</view>
						<view class="diygw-grid-title"> 点赞 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_rm.png"></image>
						</view>
						<view class="diygw-grid-title"> 热门 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-3">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid3-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_ht.png"></image>
							<view class="diygw-tag badge red"> 10 </view>
						</view>
						<view class="diygw-grid-title"> 话题 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid3-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_jb.png"></image>
							<view class="diygw-tag badge red"> 2 </view>
						</view>
						<view class="diygw-grid-title"> 证书 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid3-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_kf.png"></image>
						</view>
						<view class="diygw-grid-title"> 聊聊 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid3-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_pxb.png"></image>
						</view>
						<view class="diygw-grid-title"> 荣誉 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid3-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_dz.png"></image>
						</view>
						<view class="diygw-grid-title"> 点赞 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid3-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_rm.png"></image>
						</view>
						<view class="diygw-grid-title"> 热门 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-5">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid7-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_ht.png"></image>
							<view class="diygw-tag badge red"> 10 </view>
						</view>
						<view class="diygw-grid-title"> 话题 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid7-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_jb.png"></image>
							<view class="diygw-tag badge red"> 2 </view>
						</view>
						<view class="diygw-grid-title"> 证书 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid7-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_kf.png"></image>
						</view>
						<view class="diygw-grid-title"> 聊聊 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid7-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_pxb.png"></image>
						</view>
						<view class="diygw-grid-title"> 荣誉 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid7-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="https://lib.diygw.com/static/icon/icon1/icon1_dz.png"></image>
						</view>
						<view class="diygw-grid-title"> 点赞 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-3">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid5-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius grid5-icon-clz diy-icon-pullright"> </view>
						<view class="diygw-grid-title"> 菜单一 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid5-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius grid5-icon-clz diy-icon-skin"> </view>
						<view class="diygw-grid-title"> 菜单二 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid5-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius grid5-icon-clz diy-icon-addressbook"> </view>
						<view class="diygw-grid-title"> 菜单三 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid5-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius grid5-icon-clz diy-icon-subscription"> </view>
						<view class="diygw-grid-title"> 菜单四 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid5-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius grid5-icon-clz diy-icon-upstage"> </view>
						<view class="diygw-grid-title"> 菜单五 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid5-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius grid5-icon-clz diy-icon-ticket"> </view>
						<view class="diygw-grid-title"> 菜单六 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-4">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid6-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-pullright"> </view>
						<view class="diygw-grid-title"> 菜单一 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid6-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-skin"> </view>
						<view class="diygw-grid-title"> 菜单二 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid6-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-addressbook"> </view>
						<view class="diygw-grid-title"> 菜单三 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid6-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-subscription"> </view>
						<view class="diygw-grid-title"> 菜单四 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-4">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid8-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-pullright"> </view>
						<view class="diygw-grid-title"> 菜单一 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid8-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-skin"> </view>
						<view class="diygw-grid-title"> 菜单二 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid8-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-addressbook"> </view>
						<view class="diygw-grid-title"> 菜单三 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid8-item-clz border">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-subscription"> </view>
						<view class="diygw-grid-title"> 菜单四 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-3">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid4-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius-xs grid4-icon-clz diy-icon-pullright"> </view>
						<view class="diygw-grid-title"> 菜单一 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid4-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius-xs grid4-icon-clz diy-icon-skin"> </view>
						<view class="diygw-grid-title"> 菜单二 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid4-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius-xs grid4-icon-clz diy-icon-addressbook"> </view>
						<view class="diygw-grid-title"> 菜单三 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid4-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius-xs grid4-icon-clz diy-icon-subscription"> </view>
						<view class="diygw-grid-title"> 菜单四 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid4-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius-xs grid4-icon-clz diy-icon-upstage"> </view>
						<view class="diygw-grid-title"> 菜单五 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid4-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius-xs grid4-icon-clz diy-icon-ticket"> </view>
						<view class="diygw-grid-title"> 菜单六 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-4">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid9-item-clz border bg-green">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-pullright"> </view>
						<view class="diygw-grid-title"> 菜单一 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid9-item-clz border bg-orange">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-skin"> </view>
						<view class="diygw-grid-title"> 菜单二 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid9-item-clz border bg-olive">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-addressbook"> </view>
						<view class="diygw-grid-title"> 菜单三 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid9-item-clz border bg-blue">
						<view class="diygw-grid-icon diygw-avatar radius diy-icon-subscription"> </view>
						<view class="diygw-grid-title"> 菜单四 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-3 diygw-card diygw-shadow">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid1-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid1.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单一 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid1-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid2.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单二 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid1-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid3.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单三 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid1-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid4.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单四 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid1-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid5.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单五 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid1-item-clz">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid6.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单六 </view>
					</view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-pzx" style="border-bottom: 4px solid #eee"></view>
		</view>
		<view class="flex diygw-col-24">
			<view class="diygw-grid col-3">
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid2-item-clz diygw-card diygw-shadow">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid1.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单一 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid2-item-clz diygw-card diygw-shadow">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid2.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单二 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid2-item-clz diygw-card diygw-shadow">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid3.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单三 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid2-item-clz diygw-card diygw-shadow">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid4.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单四 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid2-item-clz diygw-card diygw-shadow">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid5.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单五 </view>
					</view>
				</view>
				<view class="diygw-grid-item">
					<view class="diygw-grid-inner grid2-item-clz diygw-card diygw-shadow">
						<view class="diygw-grid-icon diygw-avatar radius">
							<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/grid6.png"></image>
						</view>
						<view class="diygw-grid-title"> 菜单六 </view>
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
	.grid10-badge-0 {
		right: 2rpx !important;
		top: 2rpx !important;
	}
	.grid5-item-clz {
		padding: 0px;
	}
	.grid5-icon-clz {
		width: 50px;
		height: 50px;
		font-size: calc(50px - 10px) !important;
		color: rgba(4, 173, 7, 1);
	}
	.grid4-item-clz {
		padding: 10px;
	}
	.grid4-icon-clz {
		width: 40px;
		height: 40px;
		font-size: calc(40px - 10px) !important;
		color: rgba(251, 5, 5, 1);
	}
</style>
