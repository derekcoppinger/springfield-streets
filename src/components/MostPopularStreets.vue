<template>
  <div class="streets">
    <h3>Main Streets in Springfield </h3>
    <ul>
      <li>S Veterans Pkwy, Cars Driven Per Day: 215,000</li>
      <li>Dirksen Pkwy, Cars Driven Per Day: 176,000</li>
      <li>Wabash Ave, Cars Driven Per Day: 143,000</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'MostPopularStreets',
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
