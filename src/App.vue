<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Notes Management Project"/>
    <Header></Header>
    <InputNote></InputNote>
    <Note></Note>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import InputNote from '@/components/InputNote.vue'
import Note from '@/components/Note.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header,
    InputNote,
    Note,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
