<script lang="ts">
	import TestComponent from '../components/TestComponent.svelte';
	const time = () => {
		return new Date().toLocaleTimeString();
	};
</script>

<h1>Welcome to SvelteKit {time()}</h1>
<TestComponent />
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
