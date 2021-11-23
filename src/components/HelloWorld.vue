<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <button class="btn btn-success mb-4">{{ btnMsg }}</button>
    <div class="alert" :class="alertType">
      Este es un mensaje de alerta!
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    btnMsg: String,
    alertType: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
