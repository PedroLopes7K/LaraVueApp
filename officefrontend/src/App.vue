<template>
  <div id="app">
    <img
      src="https://camo.githubusercontent.com/aab17e69c1befd00860da2dc9582fbde3890b236df062b784c9b33c9e986b008/68747470733a2f2f6370352e736770312e63646e2e6469676974616c6f6365616e7370616365732e636f6d2f7a6f726f2f6c6172617675652d63646e2f6c6172617675652d6c6f676f2d6c696e652e706e67">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
