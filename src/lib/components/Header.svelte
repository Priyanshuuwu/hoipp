<script>
	import AnimeSearchDrawer from "./AnimeSearchDrawer.svelte";
</script>

<header class="header">
	<a href="/">
		<h1 class="header-title">
			Mai_anime
		</h1>
	</a>

	<AnimeSearchDrawer />
</header>

<style>
	.header {
		width: 100%;
		height: 60px;
		padding: 0 1rem;
		display: flex;
		align-items: center;
		justify-content: space-between;
		background-color: #1a1c20;
	}

	.header-title {
		font-size: 1.75rem;
		font-weight: 800;
		display: flex;
		align-items: center;
		gap: 0.5rem;
	}

	.header-title:hover {
		color: #e64a19;
	}
</style>
