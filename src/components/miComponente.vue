<template>
    <div>
        <h1>{{ libro.titulo }} </h1>
        <h2>{{ libro.autor }} </h2>
    </div>
</template>

<script>
export default{
    name:"MiComponente",
    data(){
        return{
            libro: {
                autor: "Umberto eco",
                titulo: "Péndulo de Foucault"
            }
        }
    }
}
</script>
