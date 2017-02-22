<template>
  <div id="app">
    <div>{{count}}</div>
    <botton @click="increment">+</botton>
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
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
