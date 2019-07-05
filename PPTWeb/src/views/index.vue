<template>
    <div class = "box">
       <div class ="show" @click="elementClick">element</div>
    </div>
</template>

<script>
    export default {
        name: "index",
        data(){
          return {

          }
        },
        mounted(){

        },
        methods:{
          elementClick(){
            this.$message('这是一条消息提示');
          },
        }

    }
</script>

<style lang="scss">
.box{
  width: 200px;
  height: 200px;
  border:1px solid black;
  .show{
    width: 100px;
    height:100px;
    border:1px solid red;
  }
}
</style>
