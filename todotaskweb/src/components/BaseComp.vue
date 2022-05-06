<template>
  <h1>Todotask Web</h1>
  <todo-comp />
</template>

<style>
h1 {
  text-align: center;
}
</style>

<script>
import TodoComp from "./TodoComp.vue";

export default {
  name: "HelloWorld",
  components: {
    TodoComp,
  },
};
</script>
