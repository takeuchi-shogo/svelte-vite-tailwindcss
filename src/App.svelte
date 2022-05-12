<script lang="ts">
	import { Router, Link, Route } from "svelte-routing";

	import TailwindCss from './TailwindCSS.svelte'

	import TopPage from "./pages/TopPage.svelte";

	import Header from '/src/components/Header.svelte'
	import Footer from '/src/components/Footer.svelte'
</script>
<TailwindCss />

<Router>
	<main>
		<Header/>
		<TopPage/>
		<Footer/>
	</main>
</Router>