<script>
    import { AppBar } from '@skeletonlabs/skeleton';
</script>

<AppBar background="bg-black">
    <svelte:fragment slot="lead">
        <strong class="text-xl uppercase"><a href="/">Skeleton</a></strong>
    </svelte:fragment>
	
    <svelte:fragment slot="headline">
        <input type="text" class="input variant-glass">
    </svelte:fragment>
    
    <svelte:fragment slot="trail">
        <button type="submit" class="btn variant-glass">Search</button>
    </svelte:fragment>

</AppBar>