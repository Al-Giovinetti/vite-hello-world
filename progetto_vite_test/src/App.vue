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

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
