<template>
  <div class="container" id="app">
  <div class="row">
    <div class="col-sm">
      <h1>Login Page</h1>
    </div>
    <div class="col-sm">
      <input type="username" />
    </div>
    <div class="col-sm">
      <input type="password" />
    </div>
    <div class="col-sm">
      <button type="submit"> login</button>

    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Login Page'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
