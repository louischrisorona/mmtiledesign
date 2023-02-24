<template>
  <div class="main-page">
    <h1>{{ msg }}</h1>
    <p>
      Welcome to M.M. Tile Design
    </p>
    <h3>For all of your custom construction needs</h3>
    <ul>
      <li></li>
      <li></li>
    </ul>
    <h3>Services</h3>
    <ul>
      <li>1</li>
      <li>2</li>
      <li>3</li>
      <li>4</li>
      <li>5</li>
    </ul>
    <h3>Past Projects</h3>
    <ul>
      <li>A</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'MMTileDesign',
  props: {
    msg: String
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
