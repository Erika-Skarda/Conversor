<template>
  <div id="app">
    <h1 class="text-center">Conversor  de Moedas</h1>
    <div class="linha">
     <Conversor moeda-a="USD" moeda-b="BRL"/>
     <Conversor moeda-a="BRL" moeda-b="USD"/>
    </div>
        <div class="linha">
     <Conversor moeda-a="CAD" moeda-b="BRL"/>
     <Conversor moeda-a="BRL" moeda-b="CAD"/>
    </div>
        <div class="linha">
     <Conversor moeda-a="EUR" moeda-b="BRL"/>
     <Conversor moeda-a="BRL" moeda-b="EUR"/>
    </div>
  </div>
</template>

<script>
import Conversor from './components/Conversor'

export default {
  name: 'App',
  components: {
   Conversor
  }
}
</script>

<style>
#app {
  max-width: 900px;
  margin: auto;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: "#f26363";
  margin-top: 30px;
}
  .linha{
    margin-top: 40px;
    display: flex;
    justify-content: space-around;
  }
.text-center {
  text-align:center;
}

</style>
