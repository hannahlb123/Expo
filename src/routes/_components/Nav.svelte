<script>
	export let segment
</script>

<style>
	a {
		border-bottom: 1px solid white;
	}

 .is-active {
	 border-bottom: 1px solid black;
 }
</style>

<nav class="navbar">
  <div class="navbar-brand">
    <a class="navbar-item" class:is-active={segment === undefined} href=".">
			home
		</a>
  </div>
</nav>

