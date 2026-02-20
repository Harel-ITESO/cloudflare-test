<script lang="ts">
	let counter = $state(0);
</script>

<div class="p-5">
	<button
		class="cursor-pointer rounded-2xl bg-red-500 px-1 py-2 text-white transition-colors hover:bg-red-400"
		onclick={() => counter++}>Counter: {counter}</button
	>
</div>
