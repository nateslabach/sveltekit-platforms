<script>
	import { appId } from '$lib/stores/app'
    import Logo from './Logo.svelte';
</script>
  
<div class="py-10">
	<header>
	<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
		<h1 class="text-3xl font-bold leading-tight tracking-tight text-grey-900"> {$appId}</h1>
	</div>
<div class="hero-section">
  <div class="square"></div>
  <div class="square"></div>
  <div class="square"></div>
  <div class="square">
    <div class="blue-box">
      Property Management Advisory
    </div>
  </div>
</div>
And here is the corresponding CSS:

css
Copy code
.hero-section {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 80vh; 
  background-color: #f0f0f0;
}

.square {
  width: 40%;
  height: 40%;
  background-color: #123456; 
  border-radius: 10%;
  display: flex;
  justify-content: center;
  align-items: center; /* These three lines center the blue box within the square */
}

.blue-box {
  padding: 20px;
  background

	</header>
	<main>
	<div class="mx-auto max-w-7xl sm:px-6 lg:px-8">
        <Logo />
		<!-- Your content -->
	</div>
	</main>
</div>
