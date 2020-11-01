<script>
  export let segment;
</script>

<style>
  .navbar {
    background-color: #3581b8;
    height: 100px;
  }
  .title {
    line-height: 100px;
    padding-left: 20px;
    padding-right: 30px;
    color: white;
  }
  p{
    color: white;
    line-height: 100px;
  }

  

  a:hover{
    background-color: #D6EDFF;
    color: #3581b8;
    transition-duration: 0.4s;
   }
</style>

<nav class="navbar">
  <h1 class="title">Rangi Ruru Co-curricular Activities Expo</h1>
  <div class="navbar-brand">
    <a class="navbar-item" class:is-active={segment === undefined} href=".">
      <p>Home</p>
    </a>
	<a class="navbar-item" class:is-active={segment === undefined} href="./SPORTS">
      <p>Sports</p>
    </a>
	<a class="navbar-item" class:is-active={segment === undefined} href="./CLUBS">
      <p>Clubs</p>
    </a>
	<a class="navbar-item" class:is-active={segment === undefined} href="./ACTIVITIES">
      <p>Activites</p>
    </a>
	<a class="navbar-item" class:is-active={segment === undefined} href="./ARTS">
      <p>Arts</p>
    </a>
  </div>
</nav>
