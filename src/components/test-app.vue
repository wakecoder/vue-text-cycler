<template>
  <div>
    Welcome to the text-cyler test app!
    <text-cycler :items="items"></text-cycler>
  </div>
</template>

<script>
import textCycler from './text-cycler.vue'
export default {
  name: 'testApp',
  data() {
    return {
      items: ['IdleHoe', 'ScatterClockit', 'Scrumptious', 'Cadillac', 'Poopenstein']
    }
  },
  components: {
    textCycler
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
