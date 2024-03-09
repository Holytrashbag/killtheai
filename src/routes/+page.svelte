<script>
    let gameId = '';
</script>

<main class="w-screen h-screen flex flex-col justify-center items-center gap-16 bg-gradient-to-br from-sky-400 to-purple-500 text-pink-50">
    <div class="flex flex-col items-center">
        <h1 class="text-9xl font-noto italic pb-8">Masterprompter</h1>
        <p class="text-3xl font-noto">Prompt like a legend</p>
    </div>
    <div class="flex flex-col items-center gap-4">
        <input bind:value={gameId} class="w-64 h-12 rounded-xl text-zinc-950 px-2 focus:outline-orange-400" placeholder="Join a game"/>
        <button class="w-72 h-16 bg-gradient-to-tr rounded-xl from-orange-400 to-pink-400 disabled:saturate-[20%] text-3xl font-noto font-bold" disabled={gameId == ''}>Join Game</button>
        <p>or</p>
        <button class="w-72 h-16 bg-gradient-to-tr rounded-xl from-emerald-400 to-sky-400 text-3xl font-noto font-bold">Create Game</button>
    </div>
</main>
