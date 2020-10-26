<template>
  <header class="header">
    <h1>TodoList</h1>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <a href="https://www.google.com/">Google</a> |
      <a href="https://github.com/meysifk/Project---Todos">Github</a>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

*{
font-family: sans-serif;
}
  .header {
    -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=50)";  
    filter: alpha(opacity=80);
    -moz-opacity: 0.80;
    -khtml-opacity: 0.8;
    opacity: 0.8;
    /*Opacity end*/
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 127px;
    padding: 10px;
    margin: 0;
    background: #333;
    color: #fff;
    text-align: center;
  }

  .header a {
    color: #fff;
    padding-right: 5px;
    padding-bottom: 10px;
    padding-left: 5px;
    padding-top: 10px;
    text-decoration: none;
    font-size: 25px;
  }
</style>
