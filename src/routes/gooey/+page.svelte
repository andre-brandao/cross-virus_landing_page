<script>
	import Gooey from '$lib/extras/Gooey.svelte';

	let gooeyBlur = 10;

	function mouseCoords(node) {
		function handleMouseMove(event) {
			const x = event.clientX;
			const y = event.clientY;
			// offset the x and y to the center of the element
			const rect = node.getBoundingClientRect();
			const offsetX = x - rect.left - rect.width / 2;
			const offsetY = y - rect.top - rect.height / 2 + 90; // add the scroll position to the calculation

			node.style.setProperty('--x', `${offsetX}px`);
			node.style.setProperty('--y', `${offsetY}px`);

			// node.style.setProperty('--y', `${y}px`);
		}

		window.addEventListener('mousemove', handleMouseMove);

		return {
			destroy() {
				window.removeEventListener('mousemove', handleMouseMove);
			}
		};
	}
</script>

<main class="flex items-center justify-center">
	<div class="h-[200px]" use:mouseCoords>
		<Gooey blur={gooeyBlur}  class="h-full w-full">
			<div
				class="absolute left-[--x] top-[--y] -translate-x-1/2 -translate-y-1/2 w-12 h-12 rounded-full bg-cyan-300 blur-md"
			/>





<form action="">
  <input type="text" class="input" placeholder="Search..."/>
  <button class="btn">Search</button>
</form>



			<span class="p-4 bg-red-500"></span>
			<button class="btn variant-glass-primary"> Click </button>
		</Gooey>
	</div>
</main>
