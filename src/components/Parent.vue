<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <Child title="toi ten la Duong"/>
  </div>
</template>

<script>
import Child from './Child'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
      Child
  }
}
</script>

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
