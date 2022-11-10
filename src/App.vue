<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div>
    <div class="container">
          <MainLayout/>
    </div>
    
  </div>
</template>

<script>
  import MainLayout from "./components/MainLayout.vue" //4th step
export default {
  name: 'App',
  components: {
    MainLayout
  }
}
</script>

<style>
  
</style>
