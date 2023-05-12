<template>
    <div class="prueba">
        <h1>Esto es una prueba</h1>
    </div>
</template>

<script>
export default{
    name: 'prueba',
    props: {
        msg: String
    }
}
</script>

<style>
    .prueba{
        position: absolute;
        width: 100%;
        text-align: center;
    }
</style>