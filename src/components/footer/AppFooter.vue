<script>
    export default{
        name: 'AppFooter',
        
        data() {
            return {
                author: 'By Giuse',
            }
        }

    }
</script>

<template>

    <footer> 
        <h3>{{ author }}</h3>
    </footer>

</template>

<style scoped>

    footer{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 50px;
        background-color: grey;
    }

</style>