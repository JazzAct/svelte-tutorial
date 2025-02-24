<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<script>
	let name = 'Svelte';
    let src = '/tutorial/image.gif';
	let name1 = 'Rick Astley';
</script>

<h1>Hello world!</h1>

<h1>Hello {name.toUpperCase()}! </h1>


<img src={src} alt="A {name1} dances." />