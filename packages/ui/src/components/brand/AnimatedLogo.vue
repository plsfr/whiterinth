<template>
	<div>
		<svg
			class="rotate outer"
			width="100%"
			height="100%"
			viewBox="0 0 590 591"
			xmlns="http://www.w3.org/2000/svg"
			xml:space="preserve"
			style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2"
		><circle cx="295" cy="295" r="190" fill="none" stroke="currentColor" stroke-width="48" stroke-dasharray="900 300" /></svg>
		<svg
			class="rotate inner"
			width="100%"
			height="100%"
			viewBox="0 0 590 591"
			xmlns="http://www.w3.org/2000/svg"
			xml:space="preserve"
			style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2"
		><circle cx="295" cy="295" r="190" fill="none" stroke="currentColor" stroke-width="48" stroke-dasharray="900 300" /></svg>
		<svg
			width="100%"
			height="100%"
			viewBox="0 0 590 591"
			version="1.1"
			xmlns="http://www.w3.org/2000/svg"
			xml:space="preserve"
			style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2"
		><circle cx="295" cy="295" r="190" fill="none" stroke="currentColor" stroke-width="48" stroke-dasharray="900 300" /></svg>
	</div>
</template>

<style lang="scss" scoped>
div {
	height: 5rem;

	svg {
		width: 5rem;
		height: 5rem;
		position: absolute;
		&.rotate {
			animation: rotate 4s infinite linear;
			&.inner {
				animation: rotate 6s infinite linear reverse;
			}
		}
		@keyframes rotate {
			0% {
				transform: rotate(0);
			}
			100% {
				transform: rotate(360deg);
			}
		}
	}
}
</style>
