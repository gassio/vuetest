<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
    <about></about>
    <modal></modal>
    <gallery></gallery>
  </div>
</template>

<script>
import Hello from './components/pages/Hello'
import About from './components/pages/About'
import Modal from './components/modules/Modal'
import Gallery from './components/modules/Gallery'

export default {
  name: 'app',
  components: {
    Hello, About, Modal, Gallery
  }
}
</script>

<style src="../node_modules/bulma/css/bulma.css"></style>

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
