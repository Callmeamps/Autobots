<script>
    import { AppBar } from '@skeletonlabs/skeleton';
</script>
    
<!-- App Bar -->
<AppBar background="variant-glass-primary" gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">
	<svelte:fragment slot="lead">(icon)</svelte:fragment>
    <div class="btn-group variant-ringed-primary justify-center items-center">
        <a href="/" data-sveltekit-preload-data="hover">Button</a>
        <a
            href="https://github.com/skeletonlabs/skeleton"
            target="_blank"
            rel="noreferrer"
            data-sveltekit-preload-data="hover"
        >
            GitHub
        </a>
    </div>
	<svelte:fragment slot="trail">(actions)</svelte:fragment>
</AppBar>