<template>
  <div class="body-flex">
    <clock></clock>
    <todo></todo>
  </div>
</template>

<script>
  import Todo from './Todo/Todo'
  import Clock from './Clock'
  import $ from 'jquery'
  export default {
    components: {
      Clock,
      Todo
    },
    mounted () {
      $('.body-flex').height(window.innerHeight)
    }
  }
</script>

<style lang="scss">
</style>
