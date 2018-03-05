<!-- 
    **author:gyx
    **msg:Be happy! Guy!
 -->

<template>
  <div id="app">
    <div id="cover"></div>
    <Iheader></Iheader>
    <Todo></Todo>
    <Ifooter></Ifooter>
  </div>
</template>

<script>
import Iheader from './todo/header.vue'
import Ifooter from './todo/footer.jsx'
import Todo from './todo/todo.vue'

export default {
  data () {
    return {
      text: 'abcde'
    }
  },
  components: {
    Iheader,
    Ifooter,
    Todo
  }
}
</script>

<style lang="stylus" scoped="">
#app{
    position absolute
    left 0
    right 0
    top 0
    bottom 0
}
#cover{
    position absolute
    left 0
    right 0
    top 0
    bottom 0
    background-color #999
    opacity .4
    z-index -1
}
</style>