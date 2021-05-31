<template>
    <div class="header">
      <div class="header-left">
        <span class="iconfont">&#xe624;</span>
      </div>
      <div class="header-input">
        <span class="iconfont">&#xe632;</span>
        输入城市/景点、游玩主题
      </div>
      <div class="header-right">
        城市
        <span class="iconfont">&#xe64a;</span>
      </div>
    </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style scoped>
  /*@import '../../assets/styles/varibles.styl';*/
  .header{
    margin: 0;
    display: flex;
    line-height: 43px;
    background-color: #00bcd4;
    color: #ffffff;
  }
  .header-left{
    width: 32px;
    float: left;
  }
  .header-input{
    flex: 1;
    line-height: 32px;
    margin-top: 6px;
    margin-bottom: 6px;
    margin-left: 6px;
    text-align: left;
    background-color: #ffffff;
    border-radius: 2px;
    color: #cccccc;
  }
  .header-right{
    width: 62px;
    float: right;
    text-align: center;
  }

</style>
