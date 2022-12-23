<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import homepage_image from '$lib/images/homepage.webp';
</script>

<svelte:head>
	<title>Baranof Adventures</title>
	<meta name="description" content="A tour guide and boating service in Sitka, AK." />
</svelte:head>

<div class="h-screen  bg-center bg-contain" style="background: url({homepage_image})">
	<div class="mx-auto max-w-7xl">
		<main class="mx-auto  max-w-7xl px-4  sm:px-6  lg:px-8 ">
			<div class="pt-12 sm:text-center lg:text-left">
				<h1 class="font-bold tracking-tight text-white ">
					<span class="block xl:inline text-4xl sm:text-5xl md:text-6xl">Baranof Adventures</span>
					<br />
					<span class="block text-white xl:inline  sm:text-md  md:text-xl"
						>A tour guide and boating service in Sitka, AK.</span
					>
				</h1>
				<p
					class="mt-3 text-base text-white sm:mx-auto sm:mt-5 sm:max-w-xl sm:text-lg md:mt-5 md:text-xl lg:mx-0"
				>
					More info comming soon!
				</p>
			</div>
		</main>
	</div>
</div>
