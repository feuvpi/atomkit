<script lang="ts">
	import AboutSection from '$lib/components/AboutSection.svelte';
	import BentoGrid from '$lib/components/BentoGrid.svelte';
	import CallToAction from '$lib/components/CallToAction.svelte';
	import HeroSection from '$lib/components/HeroSection.svelte';
	import SpeedSection from '$lib/components/SpeedSection.svelte';
	import Stats from '$lib/components/Stats.svelte';
	import Testimonials from '$lib/components/Testimonials.svelte';
    import type { PageData } from './$types';
    
    export let data: PageData;
</script>


	<main class="space-y-16 sm:space-y-28 lg:space-y-32 pb-40 overflow-clip">
		<HeroSection/>
		<AboutSection />
		<BentoGrid />
		<SpeedSection />
		<Stats/>
		<Testimonials/>
		<CallToAction/>
	</main>