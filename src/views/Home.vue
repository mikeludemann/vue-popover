<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png">
		<HelloWorld msg="Welcome to Your Vue.js App"/>
		<popover defaulttext="Hi" popovertext="I am here!" position="bottom"/>
		<popover defaulttext="Hi" popovertext="I am here!" position="right"/>
		<popover defaulttext="Hi" popovertext="I am here!" position="left"/>
		<popover defaulttext="Hi" popovertext="I am here!" position="top"/>
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import popover from '@/components/popover.vue'

export default {
	name: 'home',
	components: {
		HelloWorld,
		popover
	}
}
</script>
