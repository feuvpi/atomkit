<script lang="ts">
	import Container from "./Container.svelte";


</script>

<section>
    <Container>
        <div class="p-[--card-padding] overflow-hidden lg:aspect-video flex rounded-[--card-border-radius] bg-gray-100 dark:bg-[--card-dark-bg]">
            <div class="max-w-4xl w-full h-fit m-auto space-y-12">
                <img src="/product-screenshot.webp" alt="tailus product screenshot" loading="lazy" width="2481" height="1626">
            </div>
        </div>
        <div class="mt-12 grid sm:grid-cols-2 gap-4 sm:gap-12 max-w-3xl w-full mx-auto">
            <div>
                <h2 class="text-gray-950 dark:text-white text-2xl font-semibold">A technology-first approach to payments and finance</h2>
            </div>
            <div class="space-y-3">
                <p class="text-gray-600 dark:text-gray-400">Natus ad ipsum pariatur autem, <span class="text-gray-950 dark:text-white font-medium">fugit laborum in atque</span> amet obcaecati? Nisi minima aspernatur, quidem nulla cupiditate nam consequatur eligendi magni adipisci.</p>
                <p class="text-gray-600 dark:text-gray-400">Nisi minima aspernatur, quidem nulla cupiditate nam consequatur eligendi magni adipisci.</p>
            </div>
        </div>
    </Container>
</section>