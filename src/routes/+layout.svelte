<script lang="ts">
	let { children } = $props();
</script>

<ul>
	<li><a href="/">Fontsource</a></li>
	<li><a href="/local">Local font</a></li>
</ul>

<div>
	{@render children?.()}
</div>
