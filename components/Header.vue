<template>
  <header>
    <nav>
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/products">Products</a></li>
        <li><a href="/cart">Cart</a></li>
        <li><a href="/profile">Profile</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style scoped>
header {
  background-color: #333;
  color: #fff;
  padding: 1rem;
}
nav ul {
  list-style: none;
  display: flex;
  justify-content: space-around;
}
nav a {
  color: #fff;
  text-decoration: none;
}
</style>
