<script setup>
import NavWrapper from './components/NavWrapper.vue'
// import GlobalCounter from './components/GlobalCounter.vue'
</script>

<template>
	<header>
		<NavWrapper />
	</header>
	<main>
		<RouterView />
	</main>
	<footer>
		<!-- <GlobalCounter /> -->
	</footer>
</template>
