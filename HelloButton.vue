<template>
  <button @click="HelloWorld">Pasar saludo por consola. </button>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    data: String,
    msg: String,
  },
  methods: {
    HelloWorld() {
      console.log('Hello world!');
    },
  },
};
</script>

<style>
</style>
