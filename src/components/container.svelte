<script>
    export let src, alt, text, link;
</script>

<div class="container w-1/4 p-12 shadow shadow-slate-500 mx-4 my-2">
    <a href={link}>
        <img {src} {alt} class="pb-4" />
        <p class="text-lg">
            {text}
        </p>
    </a>
</div>
