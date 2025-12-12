<script>
    const logos = [
        { name: 'Warby Parker', hasCaseStudy: false },
        { name: 'Glossier', hasCaseStudy: false },
        { name: 'Allbirds', hasCaseStudy: false },
        { name: 'MVMT', hasCaseStudy: false },
        { name: 'Casper', hasCaseStudy: false },
        { name: 'Away', hasCaseStudy: false },
        { name: 'Hims', hasCaseStudy: false },
        { name: 'Outdoor Voices', hasCaseStudy: false },
        { name: 'Bombas', hasCaseStudy: false },
        { name: 'Brooklinen', hasCaseStudy: false },
        { name: 'Ritual', hasCaseStudy: false },
        { name: 'Quip', hasCaseStudy: false },
        { name: 'Rothy\'s', hasCaseStudy: false },
        { name: 'Koala', hasCaseStudy: false },
        { name: 'Chubbies', hasCaseStudy: false }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest text-gray-500 font-bold mb-8">
            TRUSTED BY 5,000+ PERFORMANCE MARKETERS
        </p>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-0 border-t border-l border-gray-200">
            {#each logos as logo}
                <div class="flex items-center justify-center p-6 border-r border-b border-gray-200 h-24 relative group">
                    <span class="text-base md:text-lg font-medium text-gray-400 group-hover:text-gray-900 transition-colors">
                        {logo.name}
                    </span>
                </div>
            {/each}
        </div>
    </div>
</section>
