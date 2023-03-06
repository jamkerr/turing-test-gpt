<script lang="ts">
    let prompt: string = 'Here be a prompt';
    let text: string = 'And here be the text.';
</script>

<div class="flex flex-col items-center p-5 gap-1 text-slate-900 dark:text-white">
    <h1 class="text-3xl font-bold">Is it me or GPT?</h1>
    <p>Can you tell whether a piece of writing was written by me (a human, as far as I can tell), or ChatGPT (an AI)?</p>
    <p>We both responded to the same prompts. Below, you'll see some of our creations, and you get to guess who wrote the text: was me or ChatGPT?</p>
    <h2 class="text-2xl font-bold">Prompt</h2>
    <p>{prompt}</p>
    <h2 class="text-2xl font-bold">Text</h2>
    <p>{text}</p>

    <div class="flex flex-row gap-4">
        <button class="border-2 rounded-lg bg-pink-400 p-1">It's you</button>
        <button class="border-2 rounded-lg bg-pink-400 p-1">It's GPT</button>
    </div>
</div>
