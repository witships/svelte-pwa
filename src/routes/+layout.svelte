<script>
	import '../app.scss';
</script>

<nav>
	<a href="/">トップ</a>
	<a href="/about">アバウト</a>
</nav>

<main>
	<slot />
</main>

<style lang="scss">
	nav {
		padding: 1rem;
	}
	main {
		padding: 1rem;
	}
</style>
