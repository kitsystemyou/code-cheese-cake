<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
    Input strings {{ cheese }} View
    </p>
    <h2>AES</h2>
    Transfered : 'cheesecake'
    <h2>RSA</h2>
    plain_text
    <h2>WEP</h2>
    plane_text
  </div>
</template>

<script>
var dummy="dummy"
dummy += "errer"
export default {
  name: 'Code-CheeseCake',
  props: {
    msg: String,
    cheese: dummy
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
