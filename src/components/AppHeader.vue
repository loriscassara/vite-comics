<!-- 
	START SCRIPT
-->

<script>
	export default {
		name: 'AppHeader',
		data(){
			return {

			}
		}
	}
</script>

<!-- 
	START TEMPLATE	
-->

<template>
	<!-- header elements -->
	
	<header>
		<img src="../assets/image/dc-logo.png" alt="logo">
		<div class="link-container">
			<ul class="link-container">
				<li><a href="">CHARACTERS</a></li>
				<li><a href="">COMICS</a></li>
				<li><a href="">MOVIES</a></li>
				<li><a href="">TV</a></li>
				<li><a href="">GAMES</a></li>
				<li><a href="">COLLECTIBLES</a></li>
				<li><a href="">VIDEOS</a></li>
				<li><a href="">FANS</a></li>
				<li><a href="">NEWS</a></li>
				<li><a href="">SHOP</a></li>
			</ul>
		</div>
	</header>
</template>

<!-- 
	START STYLE
-->

<style scoped>
/* common UI elements */

header{
	margin: 0 auto;
	width: 80%;
	display: flex;
	align-items: center;
	justify-content: space-between;
}

/* header elements */

header img {
	padding: 1.5rem;
	width: 8%;
}

header img:hover { cursor: pointer; }

.link-container { display: flex; }

a {
	color: rgb(77, 77, 77);
	padding: 1rem;
	font-weight: bold;
	font-size: smaller;
}

a:hover { border-bottom: solid 3px #0c7cec; }
</style>