<template>
  <div id="login">
    <h1>{{msg}}</h1>
    <h1>{{msg}}</h1>
    <el-button @click="defclick">Default</el-button>
  </div>
</template>
<script>
  export default {
    data(){
      return {
        msg: '田东'
      }
    },
    methods: {
      defclick(){
        this.msg = 'Hello'
      }
    }
  }
</script>
<style lang="scss" scoped>
  #login{
    height: 100vh;
    background: #fe0202;
  }
</style>
