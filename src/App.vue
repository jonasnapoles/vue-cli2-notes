<template>
  <div class="container mt-5" id="app">
    <img alt="Vue logo" src="@/assets/logo.png">
    <HelloWorld msg="Welcome to Notes Management Project"/>
    <Header></Header>
    <InputNote></InputNote>
    <Note></Note>
    <DetailNote></DetailNote>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import InputNote from '@/components/InputNote.vue'
import Note from '@/components/Note.vue'
import DetailNote from '@/components/DetailNote.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header,
    InputNote,
    Note,
    DetailNote,
  }
}
</script>
