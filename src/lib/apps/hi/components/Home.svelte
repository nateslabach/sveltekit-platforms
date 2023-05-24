<script>
	import Hero from './Hero.svelte'
</script>
.home.svelte{
	display: flex;
  justify-content: space-around;
  align-items: center;
  height: 80vh; /* Adjust this value to change the height of the hero section */
  background-color: #f0f0f0; /* Change this value to the desired background color */
}

.square {
  width: 40%;
  height: 40%;
  background-color: #123456; /* Change this value to the desired square color */
  border-radius: 10%; /* Change this value to adjust the roundness of the square edges */
}
<Hero />