<script>
	import Header from '$lib/Header.svelte';
</script>

<div>
	<Header />
	<slot />
</div>

<style>
    div {
        width: 1200px;
        margin: auto;
        background-color: #ffffff;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
</style>