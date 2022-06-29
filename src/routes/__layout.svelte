<script>
	let test = 0;
</script>

<div>
	<button on:click={() => test++}>
		{ test }
	</button>
</div>

<slot />
