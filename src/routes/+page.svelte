<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Hero from '$lib/components/Hero.svelte';
    import LogoGrid from '$lib/components/LogoGrid.svelte';
    import FeatureDark from '$lib/components/FeatureDark.svelte';
    import PlatformTabs from '$lib/components/PlatformTabs.svelte';
    import Testimonial from '$lib/components/Testimonial.svelte';
    import BentoGrid from '$lib/components/BentoGrid.svelte';
    import CommunityVideoGrid from '$lib/components/CommunityVideoGrid.svelte';
    import CaseStudyCards from '$lib/components/CaseStudyCards.svelte';
    import ResearchStats from '$lib/components/ResearchStats.svelte';
    import MarketerCarousel from '$lib/components/MarketerCarousel.svelte';
    import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen bg-white">
    <Navbar />
    <main>
        <Hero />
        <LogoGrid />
        <FeatureDark />
        <PlatformTabs />
        <Testimonial />
        <BentoGrid />
        <CommunityVideoGrid />
        <CaseStudyCards />
        <ResearchStats />
        <MarketerCarousel />
    </main>

    <Footer />
</div>

