<script lang="ts">
	export let text: string;
</script>

<div class="flex-1 flex flex-grow justify-center items-center">
	<span class="white-line" />
	<span class=" text-4xl ml-4 mr-4 font-serif text-center">
		{text}
	</span>
	<span class="white-line" />
</div>

<style>
	.white-line {
		@apply border-b-white border-b-2 w-1/5 h-3;
	}
</style>
