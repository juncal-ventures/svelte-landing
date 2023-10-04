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
					<div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							width="28"
							height="28"
							viewBox="0 0 28 28"
							fill="none"
						>
							<path
								d="M13.6668 14.9774C15.5452 14.9774 17.0679 13.4547 17.0679 11.5763C17.0679 9.69799 15.5452 8.17529 13.6668 8.17529C11.7885 8.17529 10.2658 9.69799 10.2658 11.5763C10.2658 13.4547 11.7885 14.9774 13.6668 14.9774Z"
								stroke="#AEAEAE"
								stroke-width="2.26736"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M13.667 2.50684C11.2616 2.50684 8.95476 3.46236 7.25391 5.16321C5.55306 6.86406 4.59753 9.1709 4.59753 11.5763C4.59753 13.7212 5.05327 15.1247 6.29805 16.6778L13.667 25.1804L21.0359 16.6778C22.2807 15.1247 22.7364 13.7212 22.7364 11.5763C22.7364 9.1709 21.7809 6.86406 20.08 5.16321C18.3792 3.46236 16.0723 2.50684 13.667 2.50684V2.50684Z"
								stroke="#AEAEAE"
								stroke-width="2.26736"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
					</div>
					<input
						type="search"
						id="default-search"
						class="block w-full p-4 pl-12 md:p-6 md:pl-12 text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-purple-500 focus:border-purple-500"
						placeholder="Search by Location"
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
