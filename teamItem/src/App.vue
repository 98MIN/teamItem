<template>
  <div id="app">
		<zm-news></zm-news>
		<hjy></hjy>
		<syd></syd>
  </div>
</template>

<script>
import zmNews from './components/zmNews'
import hjy from './components/hjy'
import syd from './components/syd'
export default {
	name: 'App',
	components: {
		zmNews,
		hjy,
		syd
	}
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
#app{
	width: 100%;
}
</style>
