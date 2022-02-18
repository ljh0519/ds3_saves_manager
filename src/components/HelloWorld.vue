<template>
  <div >
    <div class="top">
      <div class="left">
       <van-button plain type="primary" size="large">备份</van-button>
      </div>
      <div class="right">
       <van-button plain type="primary" size="large">还原</van-button>
      </div>
   
    </div>

    <div class="table">

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
  .top {
    width: 100vw;
    height: 30vh;
    border:1px solid black;

   
  }
</style>
