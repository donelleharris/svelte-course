<script>
	let name = "Donelle";
	let age = 52;

	function incrementAge(){
		age += 1;
	}
	function decrementAge(){
		age -= 1;
	}
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}, my age is {age}!</h1>
<button on:click="{incrementAge}">Increase age</button>
<button on:click="{decrementAge}">Decrease age</button>