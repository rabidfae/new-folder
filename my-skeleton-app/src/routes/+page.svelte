<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<script>
	import Myinput from './Input.svelte';
</script>

<body class="bg-rose-700/40">
	<!-- SINGLE HTML BUTTON COMPONENT -->
	<div class="flex flex-col justify-center mx-auto bg-rose-700/40 mt-8 p-10">
		<div class="flex flex-col p-5 mx-auto">
			<Myinput type="flat" size="md" />
		</div>
		<div class="flex flex-col p-5 mx-auto">
			<Myinput type="regular" size="md" />
		</div>
		<div class="flex flex-col p-5 mx-auto">
			<Myinput type="fourth" size="md" />
		</div>
		<div class="flex flex-col p-5 mx-auto">
			<Myinput type="disabled" size="md" />
		</div>
		<div class="flex flex-col p-5 mx-auto">
			<Myinput type="fifth" size="md" />
		</div>
	</div>
</body>
