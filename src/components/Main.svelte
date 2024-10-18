<script>
// @ts-nocheck

    import { disableScrollHandling } from "$app/navigation";
    import { Container } from "postcss";
</script>

<main>
    <section
        class="relative flex h-[full] shrink-0 flex-col items-center justify-center gap-8 p-4 font-display md:gap-12"
    id="intro">
        <video
            class="absolute -z-10 h-full w-full object-cover brightness-50"
            muted
            autoplay
            loop
            playsinline
            disablepictureinpicture
        >
            <source src="/main-bg.webm" type="video/webm" />
            <source src="/main-bg.MP4" type="video/mp4" />
        </video>
        <h1 class="z-10 font-extrabold text-7xl div1 mx-auto">
            Hi! I'm <span class="text-rose-600">Para</span>Doxy8k
            <br />and <span class="text-rose-600 text-9xl">welcome</span>
            <br>to my <span class="text-rose-600"> World.</span>
        </h1>
        <div style="display: flex; justify-content: center;">
            <button
              onclick="window.open('https://github.com/ParaDoxy8k','_blank')"
              class="lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl relative overflow-hidden px-6 py-6 pt-6 group rounded-full bg-gray-600 text-white"
            >
                <div
                  class="absolute top-0 right-full w-full h-full bg-rose-600 group-hover:translate-x-full z-0 duration-500"
                />
                <i class="fa-brands fa-github fa-beat-fade"></i>
            </button>
          </div>
        <div class="pt-12">
            <i class="fa-solid fa-chevron-down fa-bounce" style="font-size: 52px;"></i>
        </div>
    </section>
    <section
        id="about"
        class="w-full relative overflow-hidden px-5 py-16"
    >
        <div class="max-w-3xl m-auto">
        <div class="grid grid-cols-1 gap-3 p-3 lg:grid-cols-3">
            <div class="row-span-3 ">
                <img src="images/profile.JPEG" alt="" class="object-cover rounded-full drop-shadow-md">
                <div class="underpic">ParaDoxy8k</div>
            </div>
            <div class="col-span-2 text-6xl content-center text-center filter">Hello World!!!</div>
            <div class="row-span-2 col-span-2 indent-8">I'm ParaDoxy8k I'm born in AD 2002 3 DEC. I have some skill coding , fix computer and Network. When I have I watch movie and reading sometime , And I usually play game every night. </div>
          </div>
        </div>
        <div class="max-w-2xl m-auto gap-5 p-5">
            <h2 class="text-center text-xl mb-4">My Skill & Tools</h2>
            <div class="text-center mx-5 ">
                <i class="fa-solid fa-code mr-6" style="font-size: 52px;"></i>
                <i class="fa-brands fa-html5 mr-6" style="font-size: 52px;"></i>
                <i class="fa-brands fa-css3-alt mr-6" style="font-size: 52px;"></i>
                <i class="fa-brands fa-java mr-6" style="font-size: 52px;"></i>
                <i class="fa-brands fa-js mr-6" style="font-size: 52px;"></i>
                <i class="fa-brands fa-python mr-6"style="font-size: 52px;"></i>
                <i class="fa-brands fa-git-alt "style="font-size: 52px;" ></i>
            </div>
        </div>
        <div>
        </div>
        <div class="max-w-2xl m-auto gap-5 p-5">
            <div>
                <h3 class="text-center text-4xl mb-4 filter">
                    My fav girlgroup is NewJeans
                </h3>
                <p class="indent-8 text-justify">
                    NewJeans is a South Korean girl group formed by ADOR. The group is composed of five members: Minji, Hanni, Danielle, Haerin, and Hyein. They are known for their 'girl next door' image and musical stylings reminiscent of the 1990s and 2000s. 
                </p>
            </div>
            <div class="grid grid-cols-1 lg:grid-cols-5 gap-12 lg:gap-3 m-auto place-items-center">
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-5/5">
                    <img class="" src="https://encrypted-tbn3.gstatic.com/licensed-image?q=tbn:ANd9GcSQRbDQhUg61t5Jv5b6jpyRbsEsA-mKyYi1cRT-M0KoaA1u_ribhwBsiLRNIuUe-NEhczDPiPC4IUhjbAo" alt="">
                    <div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Hanni</p>
                    </div>
                </div>
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-5/5">
                    <img class="" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/20230905_Minji_%28NewJeans%29.jpg/640px-20230905_Minji_%28NewJeans%29.jpg" alt="">
                    <div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Minji</p>
                    </div>
                </div>
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-5/5">
                    <img class="" src="https://magnumx.me/wp-content/uploads/2022/12/Newjeans-member-age-2-768x1024.jpg" alt=""><div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center text-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Haerin</p>
                    </div>
                </div>
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-5/5">
                    <img class="" src="https://miro.medium.com/v2/resize:fit:800/1*KacCV3GTdHMP465WiQ0xBg.jpeg" alt=""><div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center text-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Hyein</p>
                    </div>
                </div>
                <div class="group mt-5 relative overflow-hidden rounded-2xl  w-5/5">
                    <img class="" src="https://media.atime.live/editor/content/3aae0465-5cb3-409c-988d-b34ec186e08d.jpeg" alt=""><div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center text-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Danielle</p>
                    </div>
                </div>
          </div>
        </div>
        <div>
            <h3 class="text-center text-4xl mb-4">
                My playlist
            </h3>
        </div>
        <div class=" flex justify-center">
            <!-- svelte-ignore a11y-missing-attribute -->
            <iframe class="rounded-2xl " width="560" height="315" src="https://www.youtube.com/embed/videoseries?si=ZeW1_Ej_EOlF8w9F&amp;start=1&amp;list=PLrxRx7WmXWaGLQoGIzaRBvl5iZwmM9SR_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
        
        <div class="max-w-2xl m-auto gap-5 ">
            <h4 class="text-center text-6xl sm:text-7xl md:text-8xl mt-6 p-10 filter">
                My Fav game
            </h4>
        </div>
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10 m-auto place-items-center">
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-96">
                    <img class="" src="https://www.icegif.com/wp-content/uploads/2023/04/icegif-668.gif" alt="">
                    <div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Valorant</p>
                    </div>
                </div>
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-96">
                    <img class="" src="https://64.media.tumblr.com/b56537599cfb8981d6d3c8f9b90f9c4a/303ecb25e4a05347-b1/s1280x1920/9f542e63aa7bda4cf80507cba9f7c59b8f71de96.gifv" alt="">
                    <div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Genshin Impact</p>
                    </div>
                </div>
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-96">
                    <img class="" src="https://www.khaosod.co.th/wpapp/uploads/2024/07/sssre.jpg" alt=""><div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center text-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Teamfight <br>Tactics</p>
                    </div>
                </div>
          </div>
          <div class="max-w-2xl m-auto gap-5 ">
            <h4 class="text-center text-6xl sm:text-7xl md:text-8xl mt-6 p-7 filter">
                My Fav Anime
            </h4>
        </div>
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10 m-auto place-items-center">
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-96">
                    <img class="" src="https://i.pinimg.com/originals/91/22/6d/91226d43d7b48c6cab5837cb2c4d23f1.gif" alt="">
                    <div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none text-center">Fullmetal alchemist <br> brotherhood</p>
                    </div>
                </div>
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-96">
                    <img class="" src="https://64.media.tumblr.com/9d9cc8dc3264e48c68afb7f6b4f3875d/9a104d86befcb9fe-ed/s540x810/5cc598c2a294f6d10004182d1a152d98450affab.gifv" alt="">
                    <div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">kimetsu no yaiba</p>
                    </div>
                </div>
                <div class="group mt-5 relative overflow-hidden rounded-2xl w-96">
                    <img class="" src="https://gifdb.com/images/high/dark-anime-sukuna-jujutsu-kaisen-q0s31n15yngza4mf.gif" alt=""><div class="absolute inset-0 hover flex justify-center opacity-0 group-hover:opacity-100 transition-opacity bg-black bg-opacity-50 text-white ">
                        <p class="text-2xl content-center text-center font-bold transition transform hover:-translate-y-1 motion-reduce:transition-none motion-reduce:hover:transform-none">Jujutsu Kaisen</p>
                    </div>
                </div>
          </div>
    </section>
    <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
        <div class="flex flex-col gap-2 text-center">
            <h1 class=" text-6xl sm:text-7xl md:text-8xl text-center filter p-10">
                My Projects 
            </h1>
            
        </div>
        <div>
            <p class="content-center text-center text-xl">
                I have no one projects now.
                <i class="fa-duotone fa-solid fa-face-sad-tear fa-shake" style="--fa-primary-color: #0000ff; --fa-secondary-color: #ffff00; --fa-secondary-opacity: 0.6;"></i>
            </p>
        </div>
        <!-- <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
            
        </div> -->
    </section>
    <style lang="postcss">
        section {
            @apply brightness-110;
        }

        :global([data-theme='dark']) section {
            @apply brightness-90;
        }

        @media (prefers-color-scheme: dark) {
            :global([data-theme='auto']) section {
                @apply brightness-90;
            }
        }
    </style>
</main>