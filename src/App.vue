<template>
  <div id="app">
    <header>
      <h1>Welcome to My Website</h1>
      <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
      </nav>
    </header>

    <main>
      <p>This is a basic Vue-powered website.</p>
    </main>

    <footer>
      <p>&copy; 2025 My Website</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #42b983;
  color: white;
  padding: 1rem;
  text-align: center;
}

nav a {
  margin: 0 1rem;
  color: white;
  text-decoration: none;
}

main {
  padding: 2rem;
  text-align: center;
}

footer {
  background-color: #eee;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
</style>
