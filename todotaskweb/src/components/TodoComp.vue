<template>
  <div v-for="(todo, index) in todoList" :key="index">
    <span></span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      todoList: [
        {
          title: "Viec 1",
          status: false,
        },
        {
          title: "Viec 2",
          status: false,
        },
        {
          title: "Viec 3",
          status: false,
        },
        {
          title: "Viec 4",
          status: false,
        },
      ],
    };
  },
};
</script>

<style scoped></style>
