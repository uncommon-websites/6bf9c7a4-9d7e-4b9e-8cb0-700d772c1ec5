<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons for features
	import IconSearch from "~icons/lucide/search";
	import IconShield from "~icons/lucide/shield";
	import IconBrain from "~icons/lucide/brain";
	import IconWifi from "~icons/lucide/wifi-off";
	import IconLink2 from "~icons/lucide/link-2";
	import IconLock from "~icons/lucide/lock";
</script>

<CenteredTextOnlyHero
	title="Your personal knowledge vault, always at your fingertips"
	subtitle="Stop wasting hours searching through scattered files and forgotten conversations. Our encrypted AI memory system instantly retrieves exactly what you need from your personal data, keeping everything private and secure."
	imageSrc="/generated/image-a-modern-office-environment-with-natural.webp"
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/atlassian.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/github.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/slack.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Remember everything, instantly"
	text="Stop wasting hours digging through scattered files, chats, and notes across different tools. Our encrypted AI memory system connects all your personal data so you get the exact information you need the moment you think of the question—while keeping everything completely private and secure."
/>

<Testimonials
	testimonials={[
		{
			name: "Mei Chen",
			position: "Senior Legal Counsel",
			company: "Morrison & Associates",
			quote:
				"I used to spend 3+ hours daily digging through case files and email threads to find precedents and client communications. Now I instantly retrieve exactly what I need from years of legal documents. This system has given me back 15 hours per week to focus on actual legal work instead of searching.",
			image: "/generated/image-a-professional-asian-woman-standing-in-a.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Research Director",
			company: "BioTech Innovations",
			quote:
				"Managing sensitive pharmaceutical research data across multiple tools was a nightmare. One misplaced study could cost us months. The encrypted memory vault eliminated our data fragmentation risk entirely while cutting research retrieval time from hours to seconds. We've accelerated our development timeline by 40%.",
			image: "/generated/image-a-professional-black-man-in-sharp-busine.webp"
		},
		{
			name: "Isabella Rodriguez",
			position: "Principal Consultant",
			company: "Strategic Insights Group",
			quote:
				"Client confidentiality is everything in consulting, but I was drowning in scattered project files across five different platforms. This AI memory system keeps everything private and searchable. I've reduced project prep time from 6 hours to 30 minutes, allowing me to take on 60% more clients without compromising quality.",
			image: "/generated/image-a-professional-latina-woman-in-a-contemp.webp"
		}
	]}
/>

<Features
	title="Your personal knowledge vault"
	subtitle="Stop losing information in scattered files and forgotten conversations. Our AI remembers everything so you don't have to."
	features={[
		{
			title: "Instant intelligent retrieval",
			description: "Find any piece of information in seconds with AI that understands context, not just keywords. Never waste time searching through folders and apps again.",
			icon: IconSearch
		},
		{
			title: "True local-first privacy",
			description: "Your data never leaves your device unless you choose to sync it. Complete offline functionality with zero-knowledge encryption that even we can't access.",
			icon: IconShield
		},
		{
			title: "Adaptive learning memory",
			description: "The system gets smarter with every interaction, learning your patterns and priorities. It anticipates what you need before you search for it.",
			icon: IconBrain
		},
		{
			title: "Works offline anywhere",
			description: "Access your entire knowledge base without internet connection. Perfect for sensitive work environments or when traveling with unreliable connectivity.",
			icon: IconWifi
		},
		{
			title: "Universal data capture",
			description: "Seamlessly integrates with all your existing tools and platforms. Automatically captures context from emails, documents, meetings, and web browsing.",
			icon: IconLink2
		},
		{
			title: "Military-grade security",
			description: "Enterprise-ready encryption and compliance features designed for professionals handling sensitive client data and confidential information.",
			icon: IconLock
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
