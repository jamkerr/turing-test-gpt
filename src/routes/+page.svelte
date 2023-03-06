<script lang="ts">
    let prompt: string = 'Here be a prompt';
    let text: string = 'And here be the text.';
</script>

<div class="place-content-center">
    <h1 class="text-3xl font-bold">Is it me or GPT?</h1>
    <p>Can you tell whether a piece of writing was written by me (a human, as far as I can tell), or ChatGPT (an AI)?</p>
    <p>We both responded to the same prompts. Below, you'll see some of our creations, and you get get to guess who wrote the text: was me or ChatGPT?</p>
    <h2 class="text-2xl font-bold">Prompt</h2>
    <p>{prompt}</p>
    <h2 class="text-2xl font-bold">Text</h2>
    <p>{text}</p>

    <button>It's you</button>
    <button>It's GPT</button>
</div>
