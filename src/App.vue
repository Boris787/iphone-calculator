<template>
  <div id="app">
    <Calculator />
  </div>
</template> 

<script>
import Calculator from './components/Calculator'

export default {
  components: {
    Calculator
  }
}
</script>

<style>
body {
  background-color: #222;
  margin: 0;
  padding: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial;
  font-size: 1rem;
}
</style>