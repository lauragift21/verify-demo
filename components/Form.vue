<template>
	<section class="text-gray-600 body-font">
		<div class="container px-5 py-24 mx-auto flex flex-wrap items-center">
			<div class="lg:w-3/5 md:w-1/2 md:pr-16 lg:pr-0 pr-0">
				<img src="/typingdna.svg" width="200" alt="Typing DNA Logo" />
				<h1 class="title-font font-medium text-3xl text-primary mt-4">
					Typing DNA Verify with Nuxt.js Demo
				</h1>
				<p class="leading-relaxed font-medium mt-4">
					A smarter, user-friendly authentication that replaces SMS 2FA codes,
					reducing costs by an order of magnitude.
				</p>
			</div>
			<div
				class="lg:w-2/6 md:w-1/2 bg-gray-100 rounded-lg p-8 flex flex-col md:ml-auto w-full mt-10 md:mt-0"
			>
				<h2 class="text-gray-900 text-lg font-medium title-font mb-2">
					Sign Up with Verify
				</h2>
				<p class="text-sm text-primary">Enter your details below:</p>
				<div class="flex">
					<span class="relative flex-1 mb-4 text-center">
						<input
							type="radio"
							id="phone"
							name="phone"
							class="w-full bg-white rounded border border-gray-300 focus:border-primary text-base outline-none text-gray-700 py-1 px-3 leading-8"
						/>
						<label for="phone" class="leading-7 text-sm text-gray-600"
							>Phone Number</label
						>
					</span>
					<span class="relative flex-1 mb-4 text-center">
						<input
							type="radio"
							id="email"
							name="email"
							class="w-full bg-white rounded border border-gray-300 focus:border-primarytext-base outline-none text-gray-700 py-1 px-3 leading-8"
						/>
						<label for="email" class="leading-7 text-sm text-gray-600">Email</label>
					</span>
				</div>
				<div class="relative mb-4">
					<label for="email" class="leading-7 text-sm text-gray-600">Email</label>
					<input
						type="email"
						id="email"
						name="email"
						class="w-full bg-white rounded border border-gray-300 focus:border-primary focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8"
					/>
				</div>
				<div class="relative mb-4">
					<label for="phone" class="leading-7 text-sm text-gray-600"
						>Phone Number</label
					>
					<input
						type="phone"
						id="phone"
						name="phone"
						class="w-full bg-white rounded border border-gray-300 focus:border-primary focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8"
					/>
				</div>
				<button
					class="text-white bg-primary border-0 py-2 px-8 focus:outline-none hover:bg-primary rounded text-lg"
				>
					Sign Up
				</button>
				<p class="text-xs text-gray-500 mt-3">
					Literally you probably haven't heard of them jean shorts.
				</p>
			</div>
		</div>
	</section>
</template>

<script>
export default {};
</script>

<style>
</style>