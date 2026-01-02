<script>
    const logos = [
        { name: 'Reducto', hasCaseStudy: false },
        { name: 'AtoB', hasCaseStudy: false },
        { name: 'Backbone', hasCaseStudy: false },
        { name: 'Hud', hasCaseStudy: false },
        { name: 'Aqua', hasCaseStudy: false },
        { name: 'Vanta', hasCaseStudy: false },
        { name: 'Mercury', hasCaseStudy: false },
        { name: 'Ramp', hasCaseStudy: false },
        { name: 'Brex', hasCaseStudy: false },
        { name: 'Rippling', hasCaseStudy: false }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest text-gray-500 font-bold mb-8">
            TRUSTED BY FAST-GROWING STARTUPS
        </p>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-0 border-t border-l border-gray-200">
            {#each logos as logo}
                <div class="flex items-center justify-center p-6 border-r border-b border-gray-200 h-24 relative group">
                    <span class="text-xl md:text-2xl font-bold text-gray-300 group-hover:text-gray-600 transition-colors">
                        {logo.name}
                    </span>
                </div>
            {/each}
        </div>
    </div>
</section>
