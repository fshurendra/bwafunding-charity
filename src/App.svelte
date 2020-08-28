<script>
	import CharityList from "./CharityList.svelte"
	
	let title = "Fauzi";
	setTimeout(function() {
		title ="Shurendra";
	}, 2000);
</script>

<h1>{title}</h1>
<CharityList/>

<style>
	h1 {
		color: aqua;
		font-size: 3em;
	}
</style>