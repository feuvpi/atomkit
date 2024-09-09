<script lang="ts">
	import '../app.css';
	import AppFooter from "$lib/components/AppFooter.svelte";
	import AppHeader from "$lib/components/AppHeader.svelte";
	import BaseHead from "$lib/components/BaseHead.svelte";


</script>
	
	<!DOCTYPE html>
	<html lang="en" class="scroll-smooth">
		<head>
		   <BaseHead />
		</head>
		<body class="overflow-x-hidden bg-white dark:bg-gray-950">
			<AppHeader />
			<slot />
			<AppFooter />
		</body>
	</html>