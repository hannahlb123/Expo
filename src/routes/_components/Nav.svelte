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
    width: 80px;
    text-align: center;
  }
  .navbar-item{
    width: auto;
    text-align: center;
    padding-left: 10px;
    padding-right: 10px;
  }
  a:hover{
    background-color: #a1cdee;
    color: #3581b8;
    transition-duration: 0.4s;
   }
</style>

<nav class="navbar">
  <h1 class="title">Rangi Ruru Co-curricular Activities Expo</h1>
    <a class="navbar-item" class:is-active={segment === undefined} href=".">
      <p>Home</p>
    </a>
	  <a class="navbar-item" class:is-active={segment === 'SPORTS'} href="SPORTS">
      <p>Sports</p>
    </a>
	  <a class="navbar-item" class:is-active={segment === 'CLUBS'} href="CLUBS">
      <p>Clubs</p>
    </a>
	  <a class="navbar-item" class:is-active={segment === 'ACTIVITIES'} href="ACTIVITIES">
      <p>Activites</p>
    </a>
    <a class="navbar-item" class:is-active={segment === 'MUSIC'} href="MUSIC">
      <p>Music</p>
    </a>
	  <a class="navbar-item" class:is-active={segment === 'ARTS'} href="ARTS">
      <p>Arts</p>
    </a>
</nav>
