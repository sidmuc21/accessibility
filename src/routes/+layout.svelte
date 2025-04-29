<script>
	import '../app.css';

	let { children } = $props();
</script>

<nav class="fixed top-0 w-full flex justify-evenly p-4 text-[#738591] shadow-lg bg-white">
	<a href="/" class="p-3 font-display hover:text-[#68e0ed]">What is Accessibility?</a>
	<a href="/chapter2" class="p-3 font-display hover:text-[#68e0ed]">Reading Order</a>
	<a href="/chapter3" class="p-3 font-display hover:text-[#68e0ed]">Contrast</a>
	<a href="/chapter4" class="p-3 font-display hover:text-[#68e0ed]">Responsive Design</a>
</nav>

{@render children()}