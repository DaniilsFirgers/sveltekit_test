<script>
	import Title from '$lib/title.svelte';
	import '../../styles/global.css';
</script>

<header>
	<Title title="Gaming starting page" />
	<div class="links">
		<a href="/">Home</a>
		<a href="/about">About</a>
		<a href="/guides">Guides</a>
	</div>
</header>
<main>
	<!-- page content -->
	<slot />
</main>
<footer><p>Copyright 2023 Gaming Guides</p></footer>

<style>
	header {
		display: flex;
		justify-content: center;
	}
	main {
		max-width: 960px;
		margin: 20px auto;
	}
	footer {
		text-align: center;
	}
	.links {
		text-align: auto;
	}
	a {
		margin-left: 10px;
	}
</style>
