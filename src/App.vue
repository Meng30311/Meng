<template>
  <div id="app">
    <Navbar/>
    <router-view/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'

export default {
   components:{
     Navbar,
   },
}
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Noto+Sans+TC&display=swap");
</style>
