<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="content">
      <b-form-input v-model="text" placeholder="Enter Api key"></b-form-input>
      <!-- <div class="mt-2">Value: {{ text }}</div> -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
      return {
        text: ''
      }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content {
  padding: 10%;
}

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
