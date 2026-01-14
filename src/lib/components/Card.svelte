<script lang="ts">
	import type { Snippet } from 'svelte';

	interface Props {
		icon: Snippet;
		children: Snippet;
	}

	const { icon, children }: Props = $props();
</script>

<div
	class="flex w-full flex-col items-center rounded-2xl border-b-8 border-b-bear-medium bg-white py-8 shadow-lg"
>
	<div
		class="flex h-16 w-16 items-center justify-center rounded-full border-2 border-bear-medium bg-bear-cream text-bear-dark"
	>
		{@render icon()}
	</div>

	{@render children()}
</div>
