<script>
	import Card from '$lib/Card.svelte';
	import Part1 from '$lib/Part1.svelte';
	import ContinueLinks from '$lib/ContinueLinks.svelte';
	import RightCard from '$lib/RightCard.svelte';
	import FeatureList from '$lib/FeatureList.svelte';
	import Pricing from '$lib/price/Pricing.svelte';
	import FreeTrial from '$lib/FreeTrial.svelte';
	import LeftCard from '$lib/LeftCard.svelte';
	import Hero from '$lib/Hero.svelte';
</script>

<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<Hero />
		
		<!-- <Part1 /> -->

		<!-- <LeftCard /> -->

		<Pricing />

		<!-- <ContinueLinks /> -->
		<!-- <RightCard /> -->

		<FeatureList />

		<!-- <FreeTrial /> -->
	</div>
</div>

<style lang="postcss">
	figure {
		@apply flex relative flex-col;
	}
	figure svg,
	.img-bg {
		@apply w-64 h-64 md:w-80 md:h-80;
	}
	.img-bg {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation:
			pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
			glow 5s linear infinite;
	}
	@keyframes glow {
		0% {
			@apply bg-primary-400/50;
		}
		33% {
			@apply bg-secondary-400/50;
		}
		66% {
			@apply bg-tertiary-400/50;
		}
		100% {
			@apply bg-primary-400/50;
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(1.5);
		}
	}
</style>
