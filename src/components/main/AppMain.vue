<script>
    export default {
        name: 'AppMain',
    }
</script>

<template>

    <div class="container">
        <div class="card-image">
            <img src="../assets/img/nitro.jpeg" alt="Foto">
        </div>
    </div>

</template>

<style scoped>

    .container{
        width: 800px;
        margin: auto;
        margin-top: 20px;
        display: flex;
        justify-content: center;
        border: 1px solid blue;
    }
    .card-image{
        width: 50px;
        height: 50px;
    }
    img{
        width: 100%;
    }

</style>