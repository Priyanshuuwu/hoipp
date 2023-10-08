<script>
	import AnimeSearchDrawer from "./AnimeSearchDrawer.svelte";
</script>

<header class="header">
	<a href="/">
		<h1 class="header-title">
			<svg
				width="28px"
				height="28px"
				fill="#e64a19"
				stroke="#e64a19"
				stroke-width="0"
				viewBox="0 0 24 24"
				xmlns="http://www.w3.org/2000/svg">
				<g>
					<path fill="none" d="M0 0h24v24H0z" />
					<path d="../../static/favicon.svg" />
				</g>
			</svg>

			Anima
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
