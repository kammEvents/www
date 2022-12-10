<script>
</script>

<svelte:head>
	<title>kammEvents</title>
	<meta name="description" content="kammEvents" />
	<meta property="og:title" content="kammEvents" />
	<meta property="og:image" content="https://kammevents.de/thumbnail.jpg">
</svelte:head>

<section>
<div class="header"><h1>kammEvents</h1></div>
<div class="col c1"><h2>Drone</h2></div>
<div class="col c2"><h2>Videography</h2></div>
<div class="col c3"><h2>Livestream</h2></div>
<div class="social">
	<a href="https://instagram.com/kevent_official"><i class="si si-instagram"></i></a>
	<a href="https://www.youtube.com/@kevent2954"><i class="si si-youtube"></i></a>
</div>
</section>

<style>
	h1 {
		text-align: center;
	}
	section {
		display: grid;
		grid-template-columns: 1fr 1fr 1fr; 
		grid-template-rows: 1fr min-content 1fr; 
		gap: 1rem 0px; 
		grid-template-areas:
			"header header header"
			"c1 c2 c3"
			"social social social";
	}

	.header { grid-area: header; }
	.c1 { grid-area: c1; }
	.c2 { grid-area: c2; }
	.c3 { grid-area: c3; }
	.social {
		grid-area: social;
		font-size: 2rem;
	}

	.social a:first-child {
		margin-right: 1rem;
	}

	.col {
		padding: 0 1rem;
		border-right: 2pt solid white;
		height: 4rem;
	}
	.c1 {
		text-align: right;
	}
	.c2, .social, .header {
		text-align: center;
	}
	.c3 {
		border-right: none;
	}
</style>
