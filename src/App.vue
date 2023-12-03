
<template>
  <div id="app">
    <todo-app></todo-app>
  </div>
</template>

<script>
import TodoApp from './components/TodoApp.vue'

export default {
  name: 'App',
  components:{
  TodoApp
}
}

</script>


<!-- 
// const todos = ref([]);
// const name = ref("");

// const input_content = ref("");
// const input_category = ref(null);

// const todos_asc = computed(() =>
//   todos.value.sort((a, b) => {
//     return b.createdAt - a.createdAt;
//   })
// ); -->