<template>
  <div class="server1">
    <div class="hd loadding">
      <img src="../assets/img/server/hd2x.png" alt="" title="">
    </div>
    <div class="life">
      <div class="life-in">
        <h2>有料生活是什么</h2>
        <p>有料生活是目前国内领先的O2O家庭服务平台，通过互联网 改变传统家政服务模式， 创新打造行业标准“互联网+”综合性上 门门服务业。有料生活以“让服务与被服务的人都感到幸福”为宗 旨，致力于为用户提供专业、高效、标准化的家庭生活服务及企 业服务。
        </p>
      </div>
  
    </div>
  
  
    <div class="join loadding">
      <h2>加入我们能获得什么</h2>
      <img src="../assets/img/server/more3x.png" alt="" title="">
    </div>
    <div class="flow loadding">
      <img src="../assets/img/server/flow3x.png" alt="" title="">
    </div>
    <div class="superiority">
      <h2>平台优势</h2>
      <div class="super-box clearfix">
        <div class="puper-box-in fl">
          <div><img src="../assets/img/server/add_09.png" alt="" title=""></div>
          <p>蓝海空白市场</p>
        </div>
        <div class="puper-box-in center fl">
          <div><img src="../assets/img/server/add_11.png" alt="" title=""></div>
          <p>创新商业模式</p>
        </div>
        <div class="puper-box-in fr">
          <div><img src="../assets/img/server/add_13.png" alt="" title=""></div>
          <p>丰富运营经验</p>
        </div>
      </div>
    </div>
  
    <form class="subm">
      <div>城市：<input class="input1" type="txt"></div>
      <div class="name">电话：<input class="input2" type="number"></div>
    </form>
    <button class="bgb">申请入驻</button>
  
  
    <div class="cover">
      <div class="success">
        <img class="ico" src="../assets/img/server/success.png" alt="" title="">
        <h2>提交成功</h2>
        <p>亲，请保持电话通畅</p>
        <p>我们将会马上和您联系</p>
        <img class="close" src="../assets/img/server/close.png" alt="" title="">
      </div>
    </div>
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
  body {
    background-color: #f7f7f7;
    padding-bottom: 0;
  }
  
  input {
    padding-left: 5px;
  }
  
  .hd {
    min-height: 6rem;
  }
  
  .life {
    position: relative;
    .life-in {
      position: absolute;
      top: 0;
      left: 50%;
      width: 12.24rem;
      margin-left: -6.12rem;
      text-align: center;
    }
    h2 {
      margin-top: .8rem;
      font-size: .6rem;
      line-height: .6rem;
      color: #323232;
    }
    p {
      margin-top: 1.4rem;
      text-indent: 2em;
      font-size: .44rem;
      line-height: .84rem;
      color: #323232;
    }
    height: 8.8rem;
    background-color: #fff;
    background-image: url("../assets/img/server/bg3x.png");
    background-repeat: no-repeat;
    background-size: 100% 93.18%;
    background-position: center top;
  }
  
  .join {
    position: relative;
    min-height: 13rem;
    background-color: #fbf8f1;
    h2 {
      position: absolute;
      width: 100%;
      text-align: center;
      margin-top: .8rem;
      font-size: .6rem;
      line-height: .6rem;
      color: #323232;
      z-index: 6;
    }
  }
  
  .flow {
    min-height: 10rem;
    background-color: #f7f7f7;
  }
  
  .superiority {
    background-color: #f7f7f7;
    h2 {
      text-align: center;
      padding-top: .8rem;
      font-size: .6rem;
      line-height: .6rem;
      color: #323232;
    }
    .super-box {
      position: relative;
      padding: .70rem .48rem 1.72rem .48rem;
    }
    .puper-box-in {
      width: 4rem;
      background-color: #fff;
      text-align: center;
      div {
        position: relative;
        width: 4rem;
        height: 4rem;
        img {
          position: absolute;
          top: 50%;
          left: 50%;
          margin-top: -0.7rem;
          margin-left: -.7rem;
          width: 1.4rem;
        }
      }
      p {
        width: 4rem;
        height: 1.4rem;
        font-size: .44rem;
        color: #646464;
        line-height: 1.4rem;
      }
    }
    .puper-box-in:nth-child(1) {
      div {
        background-color: #59bee9;
      }
    }
    .puper-box-in:nth-child(2) {
      div {
        background-color: #5ad2aa;
      }
    }
    .puper-box-in:nth-child(3) {
      div {
        background-color: #ffaa71;
      }
    }
    .center {
      position: absolute;
      top: .7rem;
      left: 50%;
      margin-left: -2rem;
    }
  }
  
  .subm {
    padding-left: 19.2%;
    div {
      font-size: .6rem;
      color: #323232;
      input {
        width: 6rem;
        height: 1rem;
        border-radius: 5px;
      }
      .input1 {
        border: solid 1px #15a2fd;
      }
      .input2 {
        border: solid 1px #c4c4c4;
      }
    }
    .name {
      padding-top: .32rem;
      padding-bottom: 1rem;
    }
    background-color: #f7f7f7;
  }
  
  button {
    width: 100%;
    height: 1.6rem;
    line-height: 1.6rem;
    font-size: .72rem;
    background-color: #15a2fd;
    letter-spacing: 1.5px;
    color: #ffffff;
  }
  
  .cover>.success {
    margin-left: -5.6rem;
    margin-top: -4.72rem;
  }
</style>
