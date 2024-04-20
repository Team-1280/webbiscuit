<script>
	import Navbar from '$lib/components/Navbar.svelte';
	import '../app.pcss';
	import '@fontsource/geist-mono/latin.css';
	import '@fontsource/geist-sans/latin.css';
	import '@fontsource/zilla-slab/latin.css';
</script>

<Navbar />
<div class="pt-24">
	<slot />
</div>
