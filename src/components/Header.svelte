<script>
    export let y;
    
    export let tabs = [
        { name: "Intro ", link: "#intro"},
        { name: "About me", link: "#about" },
        { name: "Projects", link: "#projects" },
        { name: "Contact", link: "#contact" }
    ];
</script>
<header
    class={"sticky z-[10] top-0 duration-200 px-6 flex items-center justify-between border-b border-solid " +
        (y > 0
            ? " py-4 bg-Neutral-950 border-transparent"
            : " py-6 bg-transparent border-transparent")}
>
    <h1 class="font-medium">
        <b class="font-bold poppins">ParaDoxy8k</b>
    </h1>
    <div class="sm:flex items-center gap-4 hidden">
        {#each tabs as tab, index}
            <a
                href={tab.link}
                class="duration-500 hover:text-rose-600"
                target={index === 4 ? "_blank" : ""}
            >
                <p>{tab.name}</p>
            </a>
        {/each}
        <!-- <button
            class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full bg-white text-slate-950"
        >
            <div
                class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
            />
            <h4 class="relative z-9">Get in touch</h4>
        </button> -->
    </div>
</header>