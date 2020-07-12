<template>
 <div id="app" style="height: 100% !important;">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
::-webkit-scrollbar {
    width: 0.5em;
    height: 0.4em;
    background: transparent;
}
::-webkit-scrollbar-corner {
    display: none;
}
::-webkit-scrollbar-thumb {
    background: #afafaf;
    border-radius: 0.2em;
}
html{
    scrollbar-color: #afafaf transparent; 
    scrollbar-width: thin;
    scrollbar-face-color: #afafaf ;
    scrollbar-track-color: transparent;
}
body {
    width:100% !important; 
    height:100% !important; 
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100% !important;
  padding: 0px;
  margin: 0px;
  /*background-color: rgb(231, 231, 231);*/
  background-color: #eef5ff;
}
body {
  margin: 0px;
}
</style>