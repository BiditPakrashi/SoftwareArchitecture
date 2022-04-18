<script>
	let name = 'Bidit';
	let number = 1;

	function incrementNumber() {
		number += 1;
	}
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}, my Number is {number}!</h1>
<button on:click="{incrementNumber}">Change Number</button>
