<template>
  <div class="home">
    <product-list-one></product-list-one>
    <product-list-two></product-list-two>
  </div>
</template>

<script>
import Productlistone from '../components/Productlistone'
import Productlisttwo from '../components/Productlisttwo'

export default {
  name: 'Home',
   components:{
    'product-list-one':Productlistone,
    'product-list-two':Productlisttwo
  },

}
</script>

<style>
body{
    font-family: Ubuntu;
    color: #555;
}
</style>