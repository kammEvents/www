<script>
	import './styles.css';
	import 'simple-icons-font/font/simple-icons.css';
</script>

<div class="app">
	<main>
		<slot />
	</main>
</div>

<footer>
	<div>
		Background by <a href="https://unsplash.com/@pawel_czerwinski?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Pawel Czerwinski</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
	</div>
	<nav>
		<a href="/">Home</a>
		<a href="/imprint">Imprint</a>
		<a href="/privacy">Privacy</a>
	</nav>
</footer>

<style>
	footer {
		margin-top: 1rem;
		height: 3rem;
		flex-shrink: 0;
		text-align: center;
		font-size: 0.7rem;
		background: linear-gradient(rgba(0,0,0,0.0), rgba(0,0,0,0.9));
	}
	nav {
		margin-top: 0.3rem;
	}
	nav a:not(:last-child) {
		margin-right: 1rem;
	}
</style>
