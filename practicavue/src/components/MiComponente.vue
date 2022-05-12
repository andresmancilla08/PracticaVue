<template>
    <div id="mi-componente">
        <h1>Este es mi componente</h1>
        <h2>{{subtitulo}}</h2>
    </div>
</template>

<script>
export default {
    name: 'MiComponente',
    data(){
        return {
            subtitulo: 'Este es el subtitulo del componente nuevo'
        }
    }
}
</script>

<style>

</style>