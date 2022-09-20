<template>
    
    <div>
        <img v-bind:src="url" v-bind:alt="nombre">
        <h2>{{ nombre }}</h2>
        <p>Descripcion del producto arre,<br>preparado con la mejor calidad</p>
        <a v-bind:src="url" target="_blank">Comprar $150</a>
    </div>

</template>

<script>
    export default{
        props:{
            url:{
                String,
            },
            nombre:{
                String,
            },
        },
    };
</script>

<style scoped>

    div{
        display: inline-block;
        text-align: center;
        border: 15px solid #3382FF;
    }
    img{
        width: 10rem;
        padding: 2rem;
        background: white;
    }
    a{
        text-decoration: none;
        color: snow;
        background: #AC78CD;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #3382FF;
    }
</style>