<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="헬로우 월드 불러올때 메세지쏴줌"
    />
    <First first="첫번째"
    />
    <h1>My TODOS</h1>
    <h2>전체: {{}} </h2>
    <h2>끝난거: {{}} </h2>
    <h2>남은거: {{}} </h2>
  </div>
</template>

<script>  //컴포넌트에 있는거 불러오기  컴포넌트에는 뷰가있다
import HelloWorld from './components/HelloWorld.vue'
import First from '@/components/First.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,First
    
  },
  data(){
    return{
      FirstFirstItem: 'init',
    }
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
