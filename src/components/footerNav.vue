<template>
  <div class="footerNav">
    <router-link to="" class="alink">{{home}}</router-link>
    <router-link to="" class="alink">{{msg}}</router-link>
    <router-link to="" class="alink">{{me}}</router-link>
  </div>
</template>

<script>
export default {
  name: 'footerNav',
  data () {
    return {
      home: '首页',
      msg: '消息',
      me: '我的',
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped less='lang'>
  .footerNav{
    position: fixed;
    width: 100%; display: flex;left: 0;bottom: 0;
    border-top:1px solid #eee;

  }
 .alink{
      flex: 1;text-align: center;height: 50px;line-height: 50px;
      font-weight: 500;font-size: 18px;
    }
</style>
