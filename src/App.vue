<template>
  <div id="app">
    <div class="container">
      <h1>{{title}}</h1>
      <p>Text</p>
      <board></board>
    </div>
  </div>
</template>

<script>
  import Board from './components/Board.vue'

  export default {
    name: 'app',
    data () {
      return {
        title: 'Memory'
      }
    },
    components: {
      board: Board,
    }
  }
</script>

<style>

</style>
