<script lang="ts">
	import { Router, Link, Route } from "svelte-routing";
</script>

<div class="bg-white pb-6 sm:pb-8 lg:pb-12">
	<div class="max-w-screen-2xl px-4 md:px-8 mx-auto">
	  <header class="flex justify-between items-center py-4 md:py-8 mb-8 md:mb-12 xl:mb-16">
		<!-- logo - start -->
		<Link to="" class="inline-flex items-center text-black-800 text-2xl md:text-3xl font-bold gap-2.5" aria-label="logo">
		  <svg width="95" height="94" viewBox="0 0 95 94" class="w-6 h-auto text-indigo-500" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
			<path d="M96 0V47L48 94H0V47L48 0H96Z" />
		  </svg>
  
		  Flowrift
		</Link>
		<!-- logo - end -->
  
		<!-- nav - start -->
		<nav class="hidden lg:flex gap-12">
			<!-- <Link to="" class="text-gray-600 hover:text-indigo-500 active:text-indigo-700 text-lg font-semibold">
				Home
			</Link> -->
			<Link to="report" class="text-gray-600 hover:text-indigo-500 active:text-indigo-700 text-lg font-semibold transition duration-100">
				Report
			</Link>
			<Link to="colume" class="text-gray-600 hover:text-indigo-500 active:text-indigo-700 text-lg font-semibold transition duration-100">
				Colume
			</Link>
			<Link to="about" class="text-gray-600 hover:text-indigo-500 active:text-indigo-700 text-lg font-semibold transition duration-100">
				About
			</Link>
			<Link to="pricing" class="text-gray-600 hover:text-indigo-500 active:text-indigo-700 text-lg font-semibold transition duration-100">
				Pricing
			</Link>
			<Link to="signin" class="text-gray-600 hover:text-indigo-500 active:text-indigo-700 text-lg font-semibold transition duration-100">
				Signin
			</Link>
		</nav>
		<!-- nav - end -->
  
		<!-- buttons - start -->
		<Link to="signin" class="hidden lg:inline-block bg-gray-200 hover:bg-gray-300 focus-visible:ring ring-indigo-300 text-gray-500 active:text-gray-700 text-sm md:text-base font-semibold text-center rounded-lg outline-none transition duration-100 px-8 py-3">
			Signin
		</Link>
  
		<button type="button" class="inline-flex items-center lg:hidden bg-gray-200 hover:bg-gray-300 focus-visible:ring ring-indigo-300 text-gray-500 active:text-gray-700 text-sm md:text-base font-semibold rounded-lg gap-2 px-2.5 py-2">
		  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 20 20" fill="currentColor">
			<path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
		  </svg>
  
		  Menu
		</button>
		<!-- buttons - end -->
	  </header>
	</div>
</div>