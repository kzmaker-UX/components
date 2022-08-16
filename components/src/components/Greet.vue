<template>
    <div>
     <h2>Hello {{ name}} a.K.a {{ heroName }}  </h2>
    </div>
</template>

<script >
    export default {
        name: "Greet", 
        props:["name", "heroName"],
        data(){
            return {
                test: "kayTesting"
            }
        }
    }
</script>

<style scoped>

</style>
