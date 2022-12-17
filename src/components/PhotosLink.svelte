<script>
	function handleClick() {
		const url =
			'http://click.pic-time.com/ls/click?upn=wwOx2YdiCM-2FEkTW9cr-2BlnlJl-2BR17hOtFDKxkHm46mGUvt61LBql-2BEZV26SSp5uYvAV3rrRephA1wM9gYF3simQ-3D-3D2SWJ_8qQxuGPM74TbPz-2BIRsVCi0-2BDNdAY1OT9RXlAUcii3aYNnW8u0rZ9QR-2FVVDjqm7WeqkCqXtLudniNNqrBj89e3gJAasMV62L0UyRUc460PrLk3u-2FlmlpWnSkFqRGGj-2BYDGLkf4exetgQNUgkPn6Edog1PmX5eMNodEpUKkcT9pC7OYmv3Rbs-2FPFxk-2BrO6v8jKtapSj7wRasdp2whTq2Jds5x88oK7kEs2o3ak-2BpsjLI9leuaF2fYBJLpJjaY8-2FyInxgpq2mOuFn7hoAdCW7ZQ3WyvIGk-2BXSJ3M-2FS6GVrHvabYkgxaTupzgIGdCUz6C8D0oC726cdTjqhyRtNFjC3breu2Gu3JO6IKfgF3YyiG9-2B3KAyLggDdC0hD2gyCaM0bwldBIX66dI8bmW3khzV1yWTgyEmpFXBmfUBMqBn75TN4aHeCN8EEa0-2BjfaQJmI7LdQdFS7-2BPOwmSQ5-2BYZ5ntPIZADIoSUErOji3dewLbCVI4CbB1V72CfzCp6yJMFOYpi';
		window.open(url, '_blank').focus();
	}
</script>

<div class="container bg-gray-200 h-64 mx-auto flex flex-col items-center justify-center">
		<div class="m-4">Les photos sont disponibles!</div>
		<button
			on:click={handleClick}
			class="bg-blue-900 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
		>
			Voir la gallerie
		</button>
</div>
