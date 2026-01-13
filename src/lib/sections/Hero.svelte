<script lang="ts">
	import { Container } from '$lib/components';
</script>

<Container class="flex flex-col items-center justify-center gap-20">
	<!-- Bear -->
	<div
		class="flex h-40 w-40 items-center justify-center rounded-full border-4 border-bear-medium bg-white shadow-2xl"
	>
		Bear Image
	</div>

	<!-- Name Tag -->
	<div
		class="w-full max-w-205 rotate-3 rounded-2xl border-6 border-bear-cream bg-white py-7.5 text-center shadow-2xl"
	>
		<h4 class="tracking-wide text-bear-medium uppercase">We Can bearly Wait</h4>
		<p class="text-sm tracking-wide uppercase">For the arrival of</p>
		<h1 class="my-8">Piper Joy</h1>
		<h4 class="text-bear-medium italic">John & Iris Nyquist</h4>
	</div>

	<!-- CTA -->
	<a
		class="rounded-full border-2 border-white bg-bear-medium px-10 py-4 font-sans text-lg font-bold text-white shadow-xl transition-transform hover:-translate-y-0.5"
		href="#rsvp">RSVP Here</a
	>

	<!-- Info Cards -->
</Container>
