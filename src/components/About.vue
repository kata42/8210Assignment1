<template>
  <div class="about">
    <h1>This is {{ their_name }}  To Do list developed in Vue.js to learn Vue.js</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data(){
    return{
      
    their_name: this.$route.params.name



      
    
    }

  }
 
}
</script>