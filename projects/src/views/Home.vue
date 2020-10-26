<template>
  <div id="app" class="container">
    <img src="../assets/logo.png" class="logo">
    <todo-list></todo-list>
  </div>
</template>

<script>
import TodoList from '../components/TodoList'


export default {
  name: 'Home',
  components: {
    TodoList
  }
}
</script>

<style>

*{
  box-sizing: border-box;
}
.container {
  max-width: 600px;
  margin: 0 auto;
  padding-top: 120px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 80px;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  font-size: 24px;
  background-image: url("../components/layout/img-bg/chevron.png");
}
.logo {
  display: block;
  margin: 20px auto;
  height: 75px;
}

</style>
