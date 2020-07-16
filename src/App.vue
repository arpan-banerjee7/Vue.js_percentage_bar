<template>
	<div id="app">
		<Post title="Post Title" />
		<Post title="Post Title 2" />
	</div>
</template>

<script>
	import Post from './components/Post';

	export default {
		name: 'app',
		components: {
			Post
		}
	}
</script>

<style lang="sass">
	body
		margin: 0
		padding: 0
		background:
			color: #F3F3F3
		#app
			padding: 25px
</style>
