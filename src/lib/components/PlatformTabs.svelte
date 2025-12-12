<script>
    // No script logic needed for this static recreation yet
</script>

<section class="py-20 bg-white font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">How It Works</span>
        <h2 class="mt-8 text-5xl md:text-7xl font-serif-display text-gray-900 leading-tight">From brand URL <br/> to high-converting ads <br/> in 4 simple steps</h2>
    </div>
    
    <!-- Tabbed interface image area -->
    <div class="max-w-7xl mx-auto mt-16 px-4">
        <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm bg-white grid md:grid-cols-12 min-h-[600px]">
             <div class="md:col-span-4 p-8 md:p-12 border-r border-gray-200 flex flex-col justify-center">
                 <h3 class="text-3xl font-serif-display mb-4">The smartest move is knowing your next</h3>
                 <p class="text-gray-600 text-base leading-relaxed mb-8">In this new era, you need to know what to create to win visitors and customers. The AirOps platform brings together your data, competitors, and audience behavior so you can create a winning SEO content strategy with ease. Filter and view action items by URL, topic, and ease of effort, giving you a clear path.</p>
                 <div>
                    <button class="text-sm font-bold border-b border-gray-300 pb-0.5 hover:border-gray-900 transition-colors">Learn More -></button>
                 </div>
             </div>
             <div class="md:col-span-8 bg-gray-50 p-8 md:p-12 flex items-center justify-center relative overflow-hidden">
                 <!-- Simplified UI Mockup -->
                 <div class="bg-white shadow-xl rounded-lg w-full h-full border border-gray-200 p-6 relative flex flex-col">
                    <div class="flex gap-2 mb-6 border-b border-gray-100 pb-4">
                        <div class="w-3 h-3 rounded-full bg-red-400"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                        <div class="w-3 h-3 rounded-full bg-green-400"></div>
                        <div class="ml-auto flex gap-2">
                            <div class="h-4 w-32 bg-gray-100 rounded-full"></div>
                        </div>
                    </div>
                    
                    <div class="space-y-6">
                        <!-- Header Stats -->
                        <div class="grid grid-cols-4 gap-4">
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Keywords</div>
                                 <div class="text-xl font-bold text-gray-900">1,240</div>
                                 <div class="text-[10px] text-green-600 font-bold">+12%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Traffic</div>
                                 <div class="text-xl font-bold text-gray-900">45.2k</div>
                                 <div class="text-[10px] text-green-600 font-bold">+8.5%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Value</div>
                                 <div class="text-xl font-bold text-gray-900">$12.4k</div>
                                 <div class="text-[10px] text-green-600 font-bold">+3.2%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Difficulty</div>
                                 <div class="text-xl font-bold text-gray-900">42</div>
                                 <div class="text-[10px] text-gray-400 font-bold">Avg</div>
                             </div>
                        </div>

                        <!-- Data Table -->
                        <div class="border border-gray-100 rounded-lg overflow-hidden">
                            <div class="bg-gray-50 px-4 py-2 border-b border-gray-100 flex text-[10px] font-bold text-gray-500 uppercase tracking-wider">
                                <div class="w-1/3">Keyword</div>
                                <div class="w-1/6 text-right">Vol</div>
                                <div class="w-1/6 text-right">KD</div>
                                <div class="w-1/6 text-right">CPC</div>
                                <div class="w-1/6 text-right">Status</div>
                            </div>
                            <div class="divide-y divide-gray-50 text-xs">
                                 {#each [
                                     {kw: 'ai content generation', vol: '12k', kd: '65', cpc: '$4.20', status: 'Rank #1'},
                                     {kw: 'seo automation tools', vol: '8.5k', kd: '54', cpc: '$3.50', status: 'Rank #3'},
                                     {kw: 'content strategy template', vol: '5.2k', kd: '42', cpc: '$1.80', status: 'Rank #5'},
                                     {kw: 'best ai writers 2024', vol: '3.1k', kd: '38', cpc: '$2.10', status: 'Rising'},
                                     {kw: 'programmatic seo guide', vol: '2.8k', kd: '45', cpc: '$5.00', status: 'New'}
                                 ] as item}
                                 <div class="px-4 py-3 flex items-center hover:bg-gray-50 transition-colors">
                                     <div class="w-1/3 font-medium text-gray-900">{item.kw}</div>
                                     <div class="w-1/6 text-right text-gray-600">{item.vol}</div>
                                     <div class="w-1/6 text-right">
                                         <span class="px-1.5 py-0.5 rounded text-[10px] font-bold {parseInt(item.kd) > 60 ? 'bg-red-100 text-red-700' : parseInt(item.kd) > 40 ? 'bg-yellow-100 text-yellow-700' : 'bg-green-100 text-green-700'}">{item.kd}</span>
                                     </div>
                                     <div class="w-1/6 text-right text-gray-600">{item.cpc}</div>
                                     <div class="w-1/6 text-right">
                                         <span class="text-[10px] font-bold text-brand-green">{item.status}</span>
                                     </div>
                                 </div>
                                 {/each}
                            </div>
                        </div>
                    </div>
                 </div>
             </div>
        </div>
        
        <!-- Bottom Grid of 4 items -->
        <div class="grid md:grid-cols-4 gap-0 mt-0 border-x border-b border-gray-200 divide-x divide-gray-200 bg-white">
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">1</div>
                <p class="text-xs text-gray-600 leading-relaxed">Paste your website URL and let AI extract your brand identity instantly.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">2</div>
                <p class="text-xs text-gray-600 leading-relaxed">AI generates fresh ad concepts daily based on current trends and best performers.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">3</div>
                <p class="text-xs text-gray-600 leading-relaxed">Customize ads with built-in editor. No design skills needed.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">4</div>
                <p class="text-xs text-gray-600 leading-relaxed">Export optimized assets for Meta and AppLovin in one click.</p>
            </div>
        </div>
    </div>
</section>