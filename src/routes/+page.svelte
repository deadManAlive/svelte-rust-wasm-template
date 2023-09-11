<script lang="ts">
    import init, { greet } from 'b2f';
    import { onMount } from 'svelte';

    onMount(() => {
        init().then(() => {
            greet("root");
        });
    });
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
