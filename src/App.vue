<template>
  <div id="app">
    <test :t_data="x"></test>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>

<script>
//引入
import test from '@/components/test.vue'

export default {
  name:'App',
  //组件注册
  components:{
    test
  },
  //data必须为函数且return
  data(){
    return{
      x: '16'
    }
  },
  //也允许其他生命周期方法
  methods: {
    
  },
}
</script>