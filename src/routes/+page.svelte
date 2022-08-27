<script>
    import Baku from "../media/Baku.svelte";
</script>

<svelte:head>
    <title>Home Page Outline</title>
    <meta name="description" content="a personal blog" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
        href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&family=Roboto:wght@300;400;500;700;900&display=swap"
        rel="stylesheet"
    />
</svelte:head>
<div class="min-h-screen">
    <div class="h-40 flex items-center">
        <h1 class="font-bold text-2xl ml-16 uppercase">LogoHere&trade;</h1>
        <ul class="mr-16 ml-auto flex flex-row antialiased">
            <li class="flex items-center justify-center mx-1">
                <a
                    class="text-sm uppercase hover:text-gray-500 transition-colors cursor-pointer"
                    href="/"
                >
                    Home
                </a>
            </li>
            <li class="flex items-center justify-center mx-1">
                <a
                    class="text-sm uppercase hover:text-gray-500 transition-colors cursor-pointer"
                    href="/blog"
                >
                    Blog
                </a>
            </li>
            <li class="flex items-center justify-center mx-1">
                <a
                    class="text-sm uppercase hover:text-gray-500 transition-colors cursor-pointer"
                    href="/contact"
                >
                    Contact
                </a>
            </li>
            <li class="flex items-center justify-center mx-1">
                <a
                    class="text-sm uppercase hover:text-gray-500 transition-colors cursor-pointer"
                    href="/about"
                >
                    About
                </a>
            </li>
        </ul>
    </div>
    <div class="h-48 flex justify-center items-center">
        <h1 class="text-6xl uppercase font-bold text-center my-48 ">home.</h1>
    </div>
    <div class="h-[200vh]" />
    <div class="h-64 flex justify-center items-center">
        <Baku className="fill-black w-1/2 mx-auto" />
    </div>
</div>
