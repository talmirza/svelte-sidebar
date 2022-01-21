<script>
	import Icon from './icon.svelte';
	import FaAt from 'svelte-icons/fa/FaAt.svelte';
	import FaAddressBook from 'svelte-icons/fa/FaAddressBook.svelte';
	import FaAlgolia from 'svelte-icons/fa/FaAlgolia.svelte';
	import FaAngleDoubleDown from 'svelte-icons/fa/FaAngleDoubleDown.svelte';
	import FaAmazon from 'svelte-icons/fa/FaAmazon.svelte';
</script>

<div class="fixed top-0 left-0 bg-gray-300 text-white h-screen w-24 m-0 flex flex-col shadow-lg">
	<Icon text="This sends an email">
		<svelte:fragment slot="visual">
			<FaAt />
		</svelte:fragment>
	</Icon>

	<Icon text="This opens your contacts list">
		<svelte:fragment slot="visual">
			<FaAddressBook />
		</svelte:fragment>
	</Icon>

	<Icon text="This starts a timer">
		<svelte:fragment slot="visual">
			<FaAlgolia />
		</svelte:fragment>
	</Icon>

	<Icon text="This makes you shorter">
		<svelte:fragment slot="visual">
			<FaAngleDoubleDown />
		</svelte:fragment>
	</Icon>

	<Icon text="This sells you on Amazon.">
		<svelte:fragment slot="visual">
			<FaAmazon />
		</svelte:fragment>
	</Icon>
</div>
