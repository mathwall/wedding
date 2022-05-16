<script>
	import OldFooter from '../components/OldFooter.svelte';
	import OldWebsite from '../components/OldWebsite.svelte';
	import TextWithinLine from '../components/TextWithinLine.svelte';
</script>

<div class="w-full bg-gradient-to-bl from-[#0D283A] to-[#27070A]">
	<div class="container">
		<div
			class="min-h-screen max-w-full
		bg-no-repeat bg-cover bg-center bg-[url('/us.jpg')]
		 shadow-2xl"
		>
			<div class="flex flex-col justify-end align-middle w-full h-screen bg-black/20 text-white">
				<div class="flex flex-col align-middle pb-[7em]">
					<div class="text-8xl text-center">Mathilde et Nicolas</div>
					<TextWithinLine text="24 septembre 2022" />
				</div>
			</div>
		</div>
		<div class="bg-white">
			<OldWebsite />
		</div>
		<OldFooter />
	</div>
</div>
