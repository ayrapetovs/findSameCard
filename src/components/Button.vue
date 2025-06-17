<script setup></script>

<template>
	<button class="button button--primary">
		<slot></slot>
	</button>
</template>

<style scoped lang="scss">
.button {
	display: flex;
	align-items: center;
	justify-content: center;
	height: 68px;
	border-radius: 100px;
	border: none;
	text-align: center;
	cursor: pointer;
	font-size: 24px;
	min-width: 335px;
	padding: 0 20px;
	will-change: transform;
	transition: 0.3s ease;

	&--primary {
		color: var(--white);
		background-color: var(--blue);

		&:hover {
				transform: scale(1.05);
		}
	}
}
</style>
