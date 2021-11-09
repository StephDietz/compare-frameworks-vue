<template>
<div id="app">
<div class="container">
<img src="./assets/logo.png" alt="">
<h1>Comparing JS Frameworks: This one is Vue</h1>
<div class="count">{{ count }}</div>
<button @click="increment()">Increment</button>
</div>
</div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      this.count++
    }
  }
}
</script>

<style>
  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 15px;
  }
  img {
    width: 20%;
  }
  h1 {
    font-size: 25px;
    font-weight: bold;
    margin-top: 15px;
    text-align: center;
  }
  .count {
    font-size: 45px;
    font-weight: bold;
    color: green;
    margin-top: 15px;
    margin-bottom: 15px;
  }
</style>
