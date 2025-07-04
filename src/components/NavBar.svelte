<script lang="ts">
	const navItems = {
		Home: { name: 'Home', url: '/' },
		About: { name: 'Over Mij', url: '/about' },
		Personality: { name: 'Persoonlijkheidstesten', url: '/personality' },
		Orientatie: { name: 'Oriëntiate', url: '/orientation' },
		Leadership: { name: 'Persoonlijk Leiderschap', url: '/leadership' },
		Skills: { name: 'Skills', url: '/skills' }
	};
</script>

<nav class="h-1/15 border-b bg-[#1B4965] p-4 shadow">
	<ul class="flex items-center gap-6 text-[#CAE9FF]">
		{#each Object.entries(navItems) as [key, value]}
			{#if Array.isArray(value)}
				<!-- Dropdown -->
				<li class="group relative">
					<button class="cursor-pointer font-semibold hover:bg-[#CAE9FF] hover:text-[#1B4965]">
						{key}
					</button>
					<ul
						class="absolute left-0 z-10 mt-2 rounded border bg-[#1B4965] opacity-0 shadow-md transition-opacity duration-200 group-hover:opacity-100"
					>
						{#each value as item}
							<li>
								<a
									href={item.url}
									class="block px-4 py-2 whitespace-nowrap hover:bg-[#CAE9FF] hover:text-[#1B4965]"
								>
									{item.name}
								</a>
							</li>
						{/each}
					</ul>
				</li>
			{:else}
				<!-- Single link -->
				<li>
					<a href={value.url} class="font-semibold hover:text-white">
						{value.name}
					</a>
				</li>
			{/if}
		{/each}
	</ul>
</nav>
