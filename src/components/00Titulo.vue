<template>
    <h2>0 sentimientos</h2>
    <p>{{ message }}</p>
    <label for="message">Mensaje</label><br />
    <input id="text" v-model="message" /><br />
</template>

<script>
import {ref} from "vue"
export default {
    name:'Titulo de Hoja 1',
    setup(){
        const message = ref("Mensaje enviado desde el componente Titulo")
        return {
            message
        }
    }
}
</script>