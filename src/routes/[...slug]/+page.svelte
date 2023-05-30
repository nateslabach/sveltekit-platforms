<script lang="ts">
	import PageSections from '$lib/structure/PageSections.svelte';
	import { appId } from "$lib/stores/app";

  /** @type {import('./$types').PageServerData} */
  export let data;
  
  $appId = data.appId;
</script>

<PageSections  />
