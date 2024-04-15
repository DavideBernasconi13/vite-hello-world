<template>
<HeaderComponent />
<AppTitleComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import AppTitleComponent from './components/AppTitleComponent.vue';
  export default {
    name: 'App', 
    components: {
      HeaderComponent,
      AppTitleComponent
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