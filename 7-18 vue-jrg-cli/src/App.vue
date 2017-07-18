<template>
  <div>
    <input v-model="message" type="text">
    {{message}}
    <br>
    <span v-bind:title="message1">鼠标悬停几秒钟查看此处动态绑定的提示信息！</span>
    <br>
    <ol>
      <li v-for="(todo,index) in todos" v-on:click="onClick(index,todo)">
        {{todo.text }}
      </li>
    </ol>

    <Son></Son>
  </div>
</template>
<script type="text/ecmascript-6">
  import Son from './components/Son'
  export default{
    data(){
      return{
        message: '',
        message1: '页面加载于 ' + new Date(),
        todos: [
          { text: '学习 JavaScript' },
          { text: '学习 Vue' },
          { text: '整个牛项目' }
        ]
      }
    },
    methods: {
      onClick(index,todo) {
        console.log(index)
        console.log(todo.text)
      }
    },
    components: {
      Son
    }
  }
</script>
<style>

</style>