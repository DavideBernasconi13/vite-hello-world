<template>
    <div class="jumbotron">
        <h1 class="display-4">{{mainTitle}}</h1>
        <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum, accusamus?</p>
        <hr class="my-4">
        <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
      </div>
</template>

<script>
    export default {
        name: 'HeroComponent', 
        data(){
            return{
                mainTitle: 'Questo è il jumbotron'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>