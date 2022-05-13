<template>
  <div class="first">
    <h1>123</h1>
    <h1>{{FirstFirstItem}}</h1>
  </div>
</template>

<script>
import FirstFirst from '@/components/FirstFirst'

export default {
  name: 'First',
  props: {
    first: String
  },
  components: {
    FirstFirst,
  },
  props:{
    FirstFirstItem:{
      type: String,

    }

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
