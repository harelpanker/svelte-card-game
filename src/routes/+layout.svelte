<script>
	import '../app.css';
</script>

<div class="flex min-h-100dvh flex-col justify-between">
	<div>
		<!-- <Navbar /> -->
		<main class="relative z-10 overflow-hidden py-10 xl:py-16">
			<slot />
		</main>
	</div>
	<!-- <Footer /> -->
</div>
