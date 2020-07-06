<template>
	<div>
		<div class="px-4 sm:px-6 lg:px-8">
			<the-navigation />
			<Nuxt />
		</div>
		<the-footer />
	</div>
</template>

<script>
	import theNavigation from '@/components/theNavigation'
	import theFooter from '@/components/theFooter'

	export default {
		components : { theNavigation, theFooter }
	}
</script>
