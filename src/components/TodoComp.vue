<template>
  <div class="todoList" v-for="(todo, index) in todoList" :key="index">
    <input type="checkbox" v-model="todo.status" />
    <span>{{ todo.title }}</span>
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
          ngayGiao: "",
          ngayDone: "",
        },
        {
          title: "Viec 2",
          status: false,
          ngayGiao: "",
          ngayDone: "",
        },
        {
          title: "Viec 3",
          status: false,
          ngayGiao: "",
          ngayDone: "",
        },
        {
          title: "Viec 4",
          status: false,
          ngayGiao: "",
          ngayDone: "",
        },
      ],
    };
  },
};
</script>

<style scoped>
.todoList {
  text-align: center;
  width: 1170px;
  margin: 0 auto;
}
</style>
