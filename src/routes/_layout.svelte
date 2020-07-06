<script>
	import Nav from '../components/Navigation.svelte';

	export let segment;
</script>

<style>
</style>

<div class="tm-page">
	<Nav {segment}/>
	<slot></slot>

</div>
