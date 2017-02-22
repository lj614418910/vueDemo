<template>
  <div id="app">
    <div>{{count}}</div>
    <button @click="increment" >+</button>
  </div>
</template>

<script>

export default {
  name: 'app',
  data(){
    return{
      count:0
    }
  },
  methods: {
    increment () {
      this.count++
    }
  }
}
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
  }
  button{
    background: #fff;
    border: 1px solid #000;
    padding: 5px;
    border-radius: 30%;
  }
</style>
