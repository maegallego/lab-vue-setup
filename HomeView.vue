<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ToDoList></ToDoList>
    <HelloButton></HelloButton>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import ToDoList from '@/components/ToDoList.vue';
import HelloButton from '@/components/HelloButton.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    ToDoList,
    HelloButton,
  },
};
</script>
