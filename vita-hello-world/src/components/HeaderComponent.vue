<template>
   <header>
    {{ title }}
   </header>
</template>

<script>
    export default {
        name:'HeaderComponent',
        data(){
            return{
                title:'La mia prima App con Vite'
            }
        }
    }
</script>

<style  scoped>
header{
    color: red;
    text-align: center;
    font-size: xx-large;
}
</style>