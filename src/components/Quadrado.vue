<template>
  <div class="quadrado">
    <h1>{{ calcula_quadrado(n) }}</h1>
 
  </div>
</template>

<script>
export default {
  name: 'Quadrado',
  data(){
    return {n : 4}
  },
  methods : {
      calcula_quadrado(n){
        return n ** 2 
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
