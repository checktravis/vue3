<template>
  <div class="infocard">
    <h1>Info Card</h1>
  </div>
</template>

<script>
export default {
  name: 'InfoCard',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.infocard {
  text-align: center;
  display: inline-block;
  border-radius: 5px;
  border: 1px solid grey;
  font-family: Helvetica;
  margin: 3px;
  width: 30%;
}
h3 {
  margin: 40px 0 0;
}
</style>
