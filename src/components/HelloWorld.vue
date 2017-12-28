<template>
  <div class="hello">
    <header>
      <a href="#/aqi">
        <img src="../assets/logo.png" title="上海鲜花港 - 郁金香">
      </a>
      <div class="juqu">jquery</div>
    </header>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Welcome'
    }
  },
  mounted (){
    $(".juqu").css("color","red")
  }
}
</script>

<style lang="less">
  .hello {

  }
</style>
