<script>
	export let counter = 0;
	function handleIncrement() {
		counter ++;
	}
	function handleDecrement() {
		counter --;
	}
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Counter: {counter}</h1>

<button on:click={handleDecrement}>Descrement</button>
<button on:click={handleIncrement}>Increment</button>
