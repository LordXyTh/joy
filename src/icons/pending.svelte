<script>
	export let size = 'default';
  export let white = false;
</script>

<svg
	id="pending-icon"
	xmlns="http://www.w3.org/2000/svg"
	aria-hidden="true"
	preserveAspectRatio="none"
	viewBox="0 0 100 100"
	class="icon spinning {size}"
  class:white
>
	<path
		d="M83.729 23.57a1.514 1.514 0 0 0-2.393-1.223l-5.944 4.262l-.468.336c-6.405-6.391-15.196-10.389-24.938-10.389c-13.284 0-24.878 7.354-30.941 18.201l.024.013a2.54 2.54 0 0 0 1.028 3.272l8.136 4.697a2.546 2.546 0 0 0 3.48-.932c.006-.011.009-.023.015-.034c3.591-6.404 10.438-10.747 18.289-10.747c4.879 0 9.352 1.696 12.914 4.5l-1.001.719l-5.948 4.262a1.511 1.511 0 0 0 .397 2.655l25.447 8.669a1.51 1.51 0 0 0 1.994-1.433l-.091-26.828z"
	/>
	<path
		d="M79.904 61.958l-.002-.001l-8.136-4.697a2.546 2.546 0 0 0-3.48.932c-.006.011-.009.023-.015.034c-3.591 6.404-10.438 10.747-18.289 10.747c-4.879 0-9.352-1.696-12.914-4.5l1.001-.719l5.948-4.262a1.511 1.511 0 0 0-.397-2.655l-25.447-8.669a1.51 1.51 0 0 0-1.994 1.433l.092 26.828a1.514 1.514 0 0 0 2.393 1.223l5.944-4.262l.468-.336c6.405 6.391 15.196 10.389 24.938 10.389c13.284 0 24.878-7.354 30.941-18.201l-.025-.012a2.54 2.54 0 0 0-1.026-3.272z"
	/>
</svg>

<style>
	#pending-icon {
		width: 1.5rem;
	}
	#pending-icon.small {
		width: 1rem;
	}
	#pending-icon.medium {
		width: 3rem;
	}
	#pending-icon.large {
		width: 5rem;
	}

	.spinning {
		animation: spin 2s linear infinite;
	}
	@keyframes spin {
		0% {
			transform: rotate(0deg);
		}
		100% {
			transform: rotate(360deg);
		}
	}
</style>
