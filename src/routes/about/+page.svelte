<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Privacy first",
			description: "Your data stays yours with encrypted, local-first architecture that never compromises security."
		},
		{
			title: "Intelligence amplified",
			description: "AI that learns your patterns and retrieves exactly what you need, when you need it."
		},
		{
			title: "Efficiency unleashed",
			description: "Transform hours of searching through scattered systems into instant knowledge retrieval."
		}
	];
</script>

<SecondaryHero
	title="Your mind deserves better than scattered chaos"
	subtitle="We built the AI memory system that transforms how knowledge workers think, store, and retrieve everything that matters."
	imageSrc="/generated/image-a-diverse-group-of-people-collaborating-.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and Investors sections removed as no team members or investors are confirmed for this AI memory/brain platform company -->

<!-- CTA Section -->
<CallToAction
	title="Stop searching. Start knowing."
	subtitle="Transform your workflow in minutes"
	description="Join thousands of knowledge workers who've reclaimed their time by turning scattered information into instant, intelligent retrieval. Your brain deserves better than endless searching."
	imageSrc="/generated/image-a-professional-knowledge-worker-standing.webp"
/>
