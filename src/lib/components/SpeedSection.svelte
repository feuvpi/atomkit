<script lang="ts">
import { cn } from "$lib/utils";
	import Container from "./Container.svelte";
	import Progress from "./ui/progress/progress.svelte";


</script>

<section>
    <Container>
        <div class="text-center">
            <h2 class="text-3xl text-gray-950 dark:text-white font-semibold md:text-4xl">Faster than any alternative</h2>
            <p class="mt-4 text-gray-600 dark:text-gray-400">Harum quae dolore orrupti aut temporibus ariatur.</p>
        </div>
        <div class="my-12 p-[--card-padding] overflow-hidden lg:aspect-video flex rounded-[--card-border-radius] bg-gray-100 dark:bg-[--card-dark-bg]">
            <div class="max-w-3xl w-full h-fit m-auto space-y-12">
                <div>
                    <h3 class="text-2xl font-bold text-gray-600 dark:text-gray-400">
                        <span class="text-gray-950 dark:text-white">Islands optimize your website</span>
                        like no other web framework can.
                    </h3>
                </div>
                <div class="space-y-6">
                    <div>
                        <Progress value={98} class="bg-gradient-to-r from-primary-600 to-accent-300"/>
                        <div class="text-sm">Astro 98%</div>
                    </div>
                
                    <div>
                        <Progress value={68} class="bg-gradient-to-r from-gray-600 to-gray-400"/>
                        <div class="text-sm">Gatsby 68%</div>
                    </div>
                
                    <div>
                        <Progress value={63} class="bg-gradient-to-r from-gray-600 to-gray-400"/>
                        <div class="text-sm">Next.js 63%</div>
                    </div>
                
                    <div>
                        <Progress value={58} class="bg-gradient-to-r from-gray-600 to-gray-400"/>
                        <div class="text-sm">WordPress 58%</div>
                    </div>
                
                    <div>
                        <Progress value={54} class="bg-gradient-to-r from-gray-600 to-gray-400"/>
                        <div class="text-sm">Nuxt 54%</div>
                    </div>
                </div>
            </div>
        </div>
        <div class="grid sm:grid-cols-2 gap-4 sm:gap-12 max-w-3xl w-full mx-auto">
            <div>
                <h3 class="text-gray-950 dark:text-white text-2xl font-semibold">Development is carried out by passionate developers</h3>
            </div>
            <div class="space-y-3">
                <p class="text-gray-600 dark:text-gray-400">Natus ad ipsum pariatur autem, <span class="text-gray-950 dark:text-white font-medium">fugit laborum in atque</span> amet obcaecati? Nisi minima aspernatur, quidem nulla cupiditate nam consequatur eligendi magni adipisci.</p>
                <p class="text-gray-600 dark:text-gray-400">Nisi minima aspernatur, quidem nulla cupiditate nam consequatur eligendi magni adipisci.</p>
            </div>
        </div>
    </Container>
</section>