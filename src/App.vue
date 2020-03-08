<template>
  <div id="app">
    <demo :title="title"></demo>
  </div>
</template>

<script>
  import demo from './vue_demo/demo'
export default {
  name: 'app',
  components:{
    demo
  },
  data () {
    return {
      title: '我的vue插件'
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

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
