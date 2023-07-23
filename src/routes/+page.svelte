<script lang="ts">
    let count = 0;
</script>


<h1 class="flex justify-center p-6 text-green-400 font-bold text-5xl">
    Counter: {count}
</h1>
<div class="flex justify-center">
    <button on:click={() => count--} class="pr-4">Decrease</button>
    <button on:click={() => count++} class="pl-4">Increase</button>
</div>