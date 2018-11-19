<template>
  <div id="news-box" class="news">
    <a class="list clearfix" href="/f/home/web/html/news_details.html?article_id=120&amp;article_section_id=18&amp;date=2018-06-11">
      <div class="img">
        <div class="img-box loadding"><img src="http://ufxin.oss-cn-shenzhen.aliyuncs.com/code/file/upload/20181015/5bc44b33611d1.jpg" alt="" title="一款多功能APP-有料生活"></div>
      </div>
      <div class="f-show bg">
        <h2>一款多功能APP-有料生活</h2> <time>2018-06-11</time> </div>
    </a>
    <a class="list clearfix" href="/f/home/web/html/news_details.html?article_id=120&amp;article_section_id=18&amp;date=2018-06-11">
      <div class="img">
        <div class="img-box loadding"><img src="http://ufxin.oss-cn-shenzhen.aliyuncs.com/code/file/upload/20181015/5bc44b33611d1.jpg" alt="" title="一款多功能APP-有料生活"></div>
      </div>
      <div class="f-show bg">
        <h2>一款多功能APP-有料生活</h2> <time>2018-06-11</time> </div>
    </a>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue';
  // import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
  
  export default Vue.extend({
  
  });
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @charset "utf-8";
  
  /*! Created by Andy on 2018/5/26,email:1046788379@qq.com。*/
  
  body {
    background-color: #f0f0f0;
  }
  
  .img-box {
    height: 100%;
    img {
      height: 100%;
    }
  }
  
  .news {
    width: 100%;
    padding: 0 12px;
    .list:nth-of-type(odd) {
      .f-show {
        padding-left: 35.4918%;
        float: right;
      }
    }
    .list:nth-of-type(even) {
      .img {
        right: 0px;
      }
      .f-show {
        padding-right: 35.4918%;
        padding-left: .5rem;
      }
    }
  }
  
  .list {
    position: relative;
    margin-top: 15px;
    .f-hide {
      width: 12.8571%;
      height: 1px;
    }
    .f-show {
      padding-top: 1.7rem;
      padding-bottom: 1.8rem;
      width: 87.1429%;
      background-color: #ffffff;
      border-radius: 6px;
    }
    .img {
      position: absolute;
      top: 45%;
      width: 6.2rem;
      height: 4rem;
      margin-top: -2rem;
      background-color: #ffffff;
      box-shadow: 1px 2px 6px 0px rgba(142, 142, 142, 0.54);
    }
    h2 {
      font-size: .6rem;
      line-height: .72rem;
      letter-spacing: 0px;
      color: #323232;
    }
    time {
      font-size: .48rem;
      line-height: .48rem;
      letter-spacing: 0px;
      color: #646464;
    }
  }
  
  .right {}
  
  .left {}
</style>
