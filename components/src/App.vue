<template>
  <div>
    <Greet name="peter" heroName = "SpiderMan"/>
    <Greet name="Bruce" heroName = "Batman"/>
    <Greet :name=" name " :heroName="heroName"/>
  </div>

    <Article>
   :title= "someTitle"
    :likes="50"
    :isPublished="true"
    </Article>
  

</template>

<script >
    import Greet from "./components/greet.vue"; 
    import Article from "./components/Article.vue"
    export default {
        name: "App", 
        data(){
            return {
                name:"Kay Z", 
                heroName: "super dev", 
                someTitle:"Avengers"
            }
        }, 
        components: {
            Greet, 
            Article
        }
    }
</script>

<style scoped>

</style>
