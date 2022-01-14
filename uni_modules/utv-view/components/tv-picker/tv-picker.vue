<template>
	<view class="tv-picker">
		
		<view class="tv-picker-selection">
			<view class="tv-picker-selection-input">
				<view class="container">
					<view class="tv-picker-item" v-for="item, index in options" :key="index" :tabindex="index"><text>{{item}}</text></view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				options: [
					'啦啦啦1',
					'啦啦啦2',
					'啦啦啦3',
					'啦啦啦4',
					'啦啦啦5',
					'啦啦啦6',
					'啦啦啦7',
					'啦啦啦8'
				]
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.tv-picker{
		background: ;
	}
	.tv-picker-selection{
		display: flex;
		justify-content: center;
		align-items: center;
		position: fixed;
		top: 0;
		bottom: 0;
		left: 0;
		right: 0;
		background-color: rgba(0, 0, 0, 0.6);
	}
	.tv-picker-selection-input{
		width: 320px;
		height: 32px;
		border-radius: 8px;
		border: solid 2px #fff;
		overflow: hidden;
	}
	.tv-picker-item {
		text-align: center;
	}
	.tv-picker-item > text{
		color: #FFFFFF;
		width: 100%;
		line-height: 32px;
	}
</style>
