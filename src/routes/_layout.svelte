<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<div id="overlayer"></div>
<div class="loader">
	<div class="spinner-border text-primary" role="status">
		<span class="sr-only">Loading...</span>
	</div>
</div>

<div class="site-wrap">
	<Nav {segment}/>

	<slot></slot>
</div>
