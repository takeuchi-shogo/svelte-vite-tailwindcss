<script lang="ts">
	import { Router } from "svelte-routing";

	import TailwindCss from './TailwindCSS.svelte'

	import TopPage from "./pages/TopPage.svelte";

	import Header from './interfaces/presenters/components/Header.svelte'
	import Footer from './interfaces/presenters/components/Footer.svelte'
</script>
<TailwindCss />

<Router>
	<main>
		<Header/>
		<TopPage/>
		<Footer/>
	</main>
</Router>