<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
*{margin:0;padding:0}
ul,li{list-style: none;}
#app{
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: column;
  
}
</style>
