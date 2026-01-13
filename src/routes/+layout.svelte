<script lang="ts">
	import './layout.css';
	import { Nav } from '$lib/sections';

	let { children } = $props();
</script>

<Nav />

<div class="mt-36">
	{@render children()}
</div>
