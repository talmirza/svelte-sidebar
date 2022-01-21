<script>
	export let text;
</script>

<i class="sidebar-icon group">
	<slot name="visual" />
	<span class="sidebar-tooltip group-hover:scale-100">
		{text}
	</span>
</i>

<!-- <Icon visual={} tooltip=""/> -->
