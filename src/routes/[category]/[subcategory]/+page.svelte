<script lang="ts">
	import { page } from '$app/stores';
	
	$: category = $page.params.category;
	$: subcategory = $page.params.subcategory;
</script>

<div>
	<h1>Category: {category}</h1>
	<h2>Subcategory: {subcategory}</h2>
</div>
