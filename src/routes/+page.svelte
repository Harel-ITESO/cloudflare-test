<script lang="ts">
	let counter = $state(0);
	let doubleCounter = $derived(counter * 2);
</script>

<button
	onclick={() => counter++}
	class="p-2 text-white bg-red-500 hover:bg-red-600 transition-colors rounded-xl cursor-pointer"
	>Counter: {counter}</button
>
<p class="font-bold">Double counter: {doubleCounter}</p>
