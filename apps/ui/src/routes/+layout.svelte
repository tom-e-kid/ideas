<script>
	import Theme from '$lib/components/theme.svelte'
	import '../app.css'
</script>

<Theme>
	<div class="text-color background-color h-[100vh] w-[100vw] overflow-hidden">
		<slot />
	</div>
</Theme>
