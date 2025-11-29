<script>
	let props = $props();
</script>

<main>
	<nav>
		<div class="flex">
			<img src={props.icon} alt="WindowIcon" id="windowicon" />
			<h1>{props.name}</h1>
		</div>
	</nav>
</main>

<style lang="scss">
	main {
		margin: 10px;
		border: solid 5px rgb(150 0 0);
		border-radius: 5px;
	}
	nav {
		display: flex;
		background-color: red;
	}

	#windowicon {
		height: 100%;
	}
</style>
