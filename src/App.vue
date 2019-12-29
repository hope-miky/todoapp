<template>
  <div id="app">
   <Todos />
  </div>
</template>

<script>
import Todos from './components/Todos';

export default {
  name: 'app',
  components: {
    Todos
  },

  data() {
    return{
      todos: [
        {
          id: 1,
          tittle: "Todo one",
          completed: false
        },
        {
          id: 2,
          tittle: "Todo two",
          completed: true
        },
        {
          id: 1,
          tittle: "Todo three",
          completed: false
        }
      ]
    }
  }
}
</script>

<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
</style>
