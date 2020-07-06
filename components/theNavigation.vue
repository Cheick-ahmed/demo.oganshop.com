<template>
	<div class="py-6 text-center">
		<nav class="flex items-center justify-between">
			<div class="flex items-center">
				<div class="flex flex-col justify-center h-6">
					<span class="h-px w-6 rounded bg-black mb-1 transition-all duration-300"></span>
					<span class="h-px w-4 rounded bg-black mb-1 transition-all duration-300"></span>
					<span class="h-px w-6 rounded bg-black"></span>
				</div>
				<nuxt-link :to="{ name : '' }" class="ml-3 font-thyn text-sm">Mon compte</nuxt-link>
			</div>
			<div>
				<nuxt-link :to="{ name : '' }">
					<svg fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor" class="text-gray-900 h-6 w-6">
						<path d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
					</svg>
				</nuxt-link>
			</div>
		</nav>
	</div>
</template>