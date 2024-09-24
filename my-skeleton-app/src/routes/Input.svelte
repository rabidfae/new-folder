<script>
	export let name = "Default";
	export let type = "regular"; // regular, flat, disabled
	export let size = "md"; // sm, md, lg
	const sizes = {
		"sm" : "px-1 py-3 pr-8 pl-8",
		"md" : "px-5 py-3 pr-8 pl-4",
		"lg" : "px-7 py-5 pr-8 pl-8",
	}
</script>

{#if type=="regular"}
 <input type="text" class="placeholder-black border-2 border-blue-700 font-medium h-12 w-80 rounded-xl text-left align-middle ${(size in sizes) ? sizes[size] : sizes["md"]}" placeholder="Input Text" required>
{/if}

{#if type=="flat"}
 <input type="text" class="border-2 border-gray-300 h-12 w-80 rounded-xl text-left align-middle ${(size in sizes) ? sizes[size] : sizes["md"]}" placeholder="Input Text" required>
{/if}

{#if type=="disabled"}
 <input type="text" class="placeholder-black border-2 border-red-700 font-medium h-12 w-80 rounded-xl text-left align-middle ${(size in sizes) ? sizes[size] : sizes["md"]}" placeholder="Input Text" required>
{/if}

{#if type=="fourth"}
 <input type="text" class="placeholder-black border-2 border-gray-300 h-12 w-80 rounded-xl text-left  ${(size in sizes) ? sizes[size] : sizes["md"]}" placeholder="Input Text" required>
{/if}

{#if type=="fifth"}
 <input type="text" class="bg-gray-300 placeholder-gray-400 border-2 border-gray-200 h-12 w-80 rounded-xl text-left align-middle ${(size in sizes) ? sizes[size] : sizes["md"]}" placeholder="Input Text" required>
{/if}
  