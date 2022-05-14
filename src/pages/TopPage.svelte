<script lang="ts">

	// import logo from './assets/svelte.png'
	// import Counter from './lib/Counter.svelte'
	import { Route } from "svelte-routing";

	
	import Home from '/src/components/Home.svelte'
	import About from "/src/pages/About.svelte";
	import Pricing from "/src/pages/Pricing.svelte";
	import Signin from "/src/pages/Signin.svelte";
	import Report from '/src/components/Report.svelte'
	import Colume from '/src/components/Stats.svelte'
  
</script>
  

<!-- 子要素としてコンポーネントを渡す方法もある -->
<Route path="">
	<Home />
</Route>
<Route path="report">
	<Report />
</Route>
<Route path="colume">
	<Colume />
</Route>
<Route path="about">
	<About />
</Route>
<Route path="pricing">
	<Pricing />
</Route>
<Route path="signin">
	<Signin />
</Route>
