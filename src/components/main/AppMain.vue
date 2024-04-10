<script>
    export default {
        name: 'AppMain',
    }
</script>

<template>

    <div class="container">

            <img src="../../assets/img/nitro.jpeg" alt="Foto">

    </div>

</template>

<style scoped>

    .container{
        display: flex;
        justify-content: center;
        width: 800px;
        height: calc(100% - (50px + 70px));
        margin: auto;
        margin-top: 20px;
        margin-bottom: 20px;
        border: 1px solid black;
    }
    .card-image{
        width: 200px;
    }
    img{
        width: 100%;
        margin: 5px;
        border-radius: 10px;
    }

</style>