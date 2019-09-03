<template>
  <div class="hello">
    <b-alert show variant="primary">Primary Alert</b-alert>
    <b-alert show variant="secondary">Secondary Alert</b-alert>
    <b-alert show variant="success">Success Alert</b-alert>
    <b-alert show variant="danger">Danger Alert</b-alert>
    <b-alert show variant="warning">Warning Alert</b-alert>
    <b-alert show variant="info">Info Alert</b-alert>
    <b-alert show variant="light">Light Alert</b-alert>
    <b-alert show variant="dark">Dark Alert</b-alert>
  </div>
</template>

<script>

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods:{

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
