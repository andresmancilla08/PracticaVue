<template>
  <div class="hello color-div-1">
    <h1>{{ msg }}</h1>
    <h2>{{texto}}</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
    return {
      texto: 'Hola Mundo Cruel!!'
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
.color-div-1{
  background: lightblue;
}
</style>
