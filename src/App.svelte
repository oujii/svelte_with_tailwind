<script>
	let name = "heaven"
	let src = "favicon.png"
	let count = 0;

	const counter = () => {
		count += 1;
	}
</script>

<main>
	<h1>hello {name}</h1>
	<h3>counter: {count}</h3>
	<button on:click={counter}>Add 1 to counter</button>
	<img {src} alt="just some random shit"> <!-- bilder finns i public foldern-->

	<div class="py-10 px-4 border bg-indigo-100 border-indigo-500 shadow-lg">
		hejj
	</div>
	<div class="py-3 px-4 border bg-gray-500 border-indigo-500">hej</div>
</main>

<style>
	h1 {
		font-size:34px;
		text-align:center
	}
	main {
		display:flex;
		flex-direction: column;
		align-items:center;
	}
	h3 {
		font-size:40px;
	}
</style>