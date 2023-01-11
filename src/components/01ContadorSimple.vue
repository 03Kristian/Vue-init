<template>
    <h2>Contador Sencillo clic</h2>
    <h3> {{ contador }}</h3>
    <button @click="incrementar"> + </button>
    <button @click="disminuir"> - </button>
    <br />
</template>

<script>
import { ref } from "vue"
export default{
    name: "ContadorSencillo",
    setup(){
        const contador = ref(0)

        const incrementar = () =>{
            contador.value++
        }

        const disminuir = () =>{
            contador.value--
        }

        return {contador, incrementar, disminuir}
    }
}
</script>