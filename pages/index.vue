<template>
  <div>

    <div><img src="~static/logo.png" /></div>
    <ul>
      <li><nuxt-link :to="{name:'index'}">HOME</nuxt-link></li>
      <li><nuxt-link :to="{name:'about'}">ABOUT</nuxt-link></li>
      <!-- <li><nuxt-link :to="{name:'news'}">NEWS</nuxt-link></li> -->
      <li><nuxt-link :to="{name:'news',params:{newsId:3306}}">NEWS :to="{name:'news',params:{newsId:3306}}"</nuxt-link></li>
    </ul>
  </div>
</template>
 
<script>
 
export default {
  components: {
   
  }
}
</script>
 
<style>
 
</style>