<script setup>
import Header from "./components/Header.vue";
import Navbar from "./components/NavBar.vue";
import User from "./components/User.vue";
</script>

<template>
  <Navbar />
  <Header />

  <main>
    <User />
  </main>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
header {
  line-height: 1.5;
}
</style>
