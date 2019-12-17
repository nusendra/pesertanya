<script>
	import Nav from '../components/Nav.svelte';
	import Hero from '../components/Hero.svelte';
</script>

<header id="header-wrap">
	<Nav/>
	<Hero/>
</header>

<main>
	<slot></slot>
</main>