<template>
  <div id="app">
    <section id="header">
      <h1 class="title">David Arteaga</h1>
      <h3>Desarrollador web</h3>
      <hr>
    </section>
    <ul>
      <li><a target="_blank" href="http://twitter.com/soydavidarteaga"><i class="fab fa-twitter"></i></a></li>
      <li><a target="_blank" href="https://instagram.com/yosoydavidarteaga"><i class="fab fa-instagram"></i></a></li>
      <li><a target="_blank" href="https://medium.com/soydavidarteaga"><i class="fab fa-medium"></i></a></li>
      <li><a target="_blank" href="http://linkedin.com/david7art"><i class="fab fa-linkedin"></i></a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Roboto+Mono:300,400');
body{
  background:#000;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background:#000;
  margin-top: 250px;
}

#header {
  line-height: 0.2;
  h1{
    text-align: center;
    font-family: 'Roboto Mono', monospace;
    color: #fff;
    font-size: 2.8rem;
    font-weight: 400;
  }
  h3{
    color:#fff;
    font-family: 'Roboto Mono',monospace;
    font-weight: 300;
  }
  hr{
    border: 10px solid #002858;
    margin-left:25%;
    margin-right: 25%;
  }
}

h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 5%;
}

a {
  color: #fff;
  font-size: 2rem;
}
</style>
