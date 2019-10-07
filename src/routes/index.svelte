<style>
	body {
		background-color: blueviolet;
	}

	h1, figure, p, button {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	button {
		font-size: 2em;
		margin: 0 0 0.5em 0
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}

</style>

<script>
	import Button from '../components/Button.svelte'
</script>

<svelte:head>
	<title>Looking for a side project?</title>
</svelte:head>

<h1>Looking for a side project?</h1>
<Button buttonText={'Yes'} />
<Button buttonText={"What's a side project?"} />
<Button buttonText={'Why should I have one?'} />

<!-- <figure>
	<img alt='Borat' src='great-success.png'>
	<figcaption>HIGH FIVE!</figcaption>
</figure>

<p><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p> -->
