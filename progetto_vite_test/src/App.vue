<script>
import AppTitle from './components/AppTitle.vue';
import JumboTrone from './components/JumboTrone.vue';
export default{
name : "AppMain",
components :{
  AppTitle,
  JumboTrone
}
}

</script>

<template>
    <AppTitle /> 
    <JumboTrone />
</template>

<style>
      body{
        text-align: center;
      }
</style>
