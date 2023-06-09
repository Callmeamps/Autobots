<script>
	
	import ActivityCard from "../lib/components/ActivityCard.svelte";
	import SavedItem from "../lib/components/SavedItem.svelte";
	
</script>

<div id="history" class="mx-9 my-3 flex card variant-filled-surface">
	<ActivityCard />
</div>
<div id="saves" class="mx-9 my-3 card py-9 px-3 h-50">
	<SavedItem />
</div>
<div id="favourites" class="mx-9 my-3 card py-9 px-3 h-50">
	Favourites
</div>