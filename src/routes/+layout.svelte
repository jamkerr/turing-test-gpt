<script>
    import "../app.css";

    let dark = true;

</script>

<div class:dark>
    <nav>
        <a href="/">home</a>
        <a href="/" on:click|preventDefault={ () => {
            dark = !dark;
        }}>{dark ? 'dark' : 'light'}</a>
    </nav>

    <main class="min-h-screen bg-white dark:bg-slate-800">
        <slot />
    </main>
</div>