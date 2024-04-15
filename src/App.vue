<template>
<AppTitleComponent />
<HeroComponent />
</template>

<script>
import AppTitleComponent from './components/AppTitleComponent.vue'
import HeroComponent from './components/HeroComponent.vue'
  export default {
    name: 'App', 
    components: {
      AppTitleComponent, 
      HeroComponent
    },
    data(){
      return{
        title: 'Hello wordl!'
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>