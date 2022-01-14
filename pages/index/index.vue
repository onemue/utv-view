<template>
	<view class="content">
		<utv-horizontal>
			<utv-block class="utv-block"></utv-block>
			<utv-block class="utv-block"></utv-block>
			<utv-block class="utv-block"></utv-block>
		</utv-horizontal>
		<utv-vertical>
			<utv-block class="utv-block"></utv-block>
			<utv-block class="utv-block"></utv-block>
			<utv-block class="utv-block"></utv-block>
		</utv-vertical>
		<tv-picker></tv-picker>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.utv-block{
		width: 32px;
		height: 32px;
		margin: 4px;
		background-color: #007AFF;
	}
</style>
