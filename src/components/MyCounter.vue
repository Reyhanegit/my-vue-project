<template>
    <div>
      <h1>{{ count }}</h1>
      <button @click="decrease">DECREASE</button>
      <button @click="reset">RESET</button>
      <button @click="increase">INCREASE</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'MyCounter',
    data() {
      return {
        count: 0
      };
    },
    methods: {
      increase() {
        this.count++;
      },
      decrease() {
        this.count--;
      },
      reset() {
        this.count = 0;
      }
    }
  };
  </script>
  
  <style scoped>

</style>
  