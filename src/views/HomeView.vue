<script>
import WatchCounter from "../components/04VerContador.vue";
import ReactiveCounter from "../components/03ContadorReactivo.vue"
import ContadorSencillo from "../components/01ContadorSimple.vue"
import Contexto1 from "../components/00Titulo.vue";
export default {
  name: 'Home',
  components:{
    WatchCounter,
    ReactiveCounter,
    ContadorSencillo,
    Contexto1,
  }
}
</script>
  
<template>
  <WatchCounter/>
  <hr/>
  <ReactiveCounter/>
  <hr/>
  <ContadorSencillo/>
  <hr/>
  <Contexto1/>
</template>
