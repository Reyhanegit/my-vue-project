<template>
  <div id="app">
    <my-counter></my-counter>
  </div>
</template>

<script>
import MyCounter from './components/MyCounter.vue';

export default {
  name: 'App',
  components: {
    MyCounter
  }
}
</script>

<style>
body {
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f4f4f4;
  margin: 0;
}

#app {
  text-align: center;
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

button {
  margin: 5px;
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  background-color: #007BFF;
  color: white;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background-color: #0056b3;
}
</style>
