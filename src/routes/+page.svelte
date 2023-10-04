<svelte:head>
	<title>AffBoost</title>
	<meta
		name="description"
		content="AffBoost"
	/>
</svelte:head>

<section id="hero" class=" px-6 pt-12 bg-gray-100">
	<div class="grid max-w-screen-xl py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-0 lg:pt-16 lg:grid-cols-12">
		<div class="mr-auto place-self-center lg:col-span-7">
			<h1
				class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl"
			>
				AffBoost
				<span class="underline underline-offset-2 decoration-8 decoration-purple-400">Newsletter</span
				>
			</h1>
			<p class="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl">
				Get best odds and featured games directly to your <a
					class="text-purple-400"
					href="#"><strong>inbox</strong></a
				>. Boost your sports betting today!
			</p>

			<form>
				<label
					for="default-search"
					class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Join Newsletter</label
				>
				<div class="relative">
					
					<input
						type="search"
						id="default-search"
						class="block w-full p-4 pl-12 md:p-6 md:pl-12 text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-purple-500 focus:border-purple-500"
						placeholder="Join newsletter"
						required
					/>
					<button
						type="submit"
						class="text-white absolute right-1.5 bottom-1.5 md:bottom-2.5 bg-purple-700 hover:bg-purple-800 focus:ring-4 focus:outline-none focus:ring-purple-300 font-medium rounded-lg text-sm md:text-lg px-3 md:px-10 py-3"
						>Join</button
					>
				</div>
			</form>
		</div>
		<div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
			<img src="/images/house1.png" width="617" height="697" alt="House" />
		</div>
	</div>
</section>
