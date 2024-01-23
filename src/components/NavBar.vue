<script></script>
<template>
  <nav>
    <span>Tutorial for Vue</span>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Login</a></li>
    </ul>
  </nav>
</template>
<style scoped>
nav {
  padding: 5px; /* Corrigido */
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #cae7e8;
}
ul {
  display: flex;
  list-style-type: none;
}
ul li {
  padding: 0.5em; /* Corrigido */
}
ul li a {
  /* Corrigido */
  text-decoration: none;
  color: #117177;
}
</style>
