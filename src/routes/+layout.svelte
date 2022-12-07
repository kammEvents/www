<script>
	import './styles.css';
</script>

<div class="app">
	<main>
		<slot />
	</main>
</div>

<footer>
	Background by <a href="https://unsplash.com/@pawel_czerwinski?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Pawel Czerwinski</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</footer>

<style>
	footer {
		height: 2rem;
		flex-shrink: 1;
		text-align: center;
		font-size: 0.7rem;
	}
</style>
