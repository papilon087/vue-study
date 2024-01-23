<script setup>
import { reactive } from "vue";
// const name = ref("Ademir Gustavo");
// const date = ref(0);
// const age = ref(25);

const person = reactive({
  name: "",
  date: 0,
  age: 0,
});

console.log(age.value);
</script>
<template>
  <div>
    <form class="form">
      <label for="name">Name:</label><br />
      <input type="text" id="name" name="name" v-model="name" /><br />
      <label for="date">Date of birth:</label><br />
      <input type="number" id="date" name="date" v-model="date" /><br />
    </form>
  </div>
  <p style="text-align: center">{{ name }} was born in {{ date }}</p>
</template>
<style scoped>
.form {
  margin: 0 auto;
  padding: 5px;
  width: 180px;
  background-color: darkcyan;
}
</style>
