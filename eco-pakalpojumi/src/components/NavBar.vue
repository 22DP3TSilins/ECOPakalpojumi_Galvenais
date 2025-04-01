<template>
  <nav class="navbar">
    <h1>Eco Pakalpojumi</h1>
    <ul>
      <li><a href="#">Sākums</a></li>
      <li><a href="#">Produkti</a></li>
      <li><a href="#">Kontakti</a></li>
    </ul>
  </nav>
</template>

<style scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #1e3a1e;
  color: white;
  padding: 1rem 2rem;
}
.navbar ul {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}
.navbar a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}
</style>
