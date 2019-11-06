<script>
  import Tailwindcss from './Tailwindcss.svelte';
	export let name;
</script>

<Tailwindcss />

<style>
	h1 {
    @apply font-serif text-4xl text-red-800;
	}
</style>

<h1>Hello {name}!</h1>
