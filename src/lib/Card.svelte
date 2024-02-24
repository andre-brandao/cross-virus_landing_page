<script>
	export let extraClasses = '';
	export let width = 'w-32';
</script>

<div class="card aspect-square items-center justify-center flex {extraClasses} {width}">
	<slot>Vazio</slot>
</div>
