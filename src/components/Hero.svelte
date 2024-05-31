<script>
    import Header from "./Header.svelte";
	import SectionWrapper from "./SectionWrapper.svelte";
</script>

<SectionWrapper>
    <Header />
    <div class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14">
        <h2 class="text-5xl sm:text-6xl md:text-7xl lg:text-8xl max-w-[1200px] mx-auto w-full text-center">
            <span class="text-violet-400">Girlfriend</span> Customizer <span class="text-pink-600">AI</span>
        </h2>
        <button class="specialBtnDark text-3xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full">Start your Journey</button>
    </div>
</SectionWrapper>