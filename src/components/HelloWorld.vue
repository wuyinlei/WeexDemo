<template>
  <text class="message" @click="handleClick">{{msg}}</text>
</template>

<script>
  export default {
      data () {
          return {
              msg:'请你点击我！！！'
          }
      },
      methods:{
          handleClick(){
              this.msg = "谢谢点击我！！！"
          }
      }
  }

</script>

<style scoped>
  .message {
    font-size: 50px;
    color: red;
    border: #00B4FF;
    font-style: italic;
  }
</style>
