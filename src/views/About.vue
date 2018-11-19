<template>
  <div class="about1">
    <div class="about loadding">
      <img class="first" src="../assets/img/about_us/hd2x.png" alt="" title="hd">
      <img class="us" src="../assets/img/about_us/us.png" alt="" title="">
      <p>有料生活是目前国内领先的O2O家庭服务平台，通过互联网改变传统家政服务模式，创新打造行业标准“互联网+”综合性上门门服务业。有料生活以“让服务与被服务的人都感到幸福”为宗旨，致力于为用户提供专业、高效、标准化的家庭生活服务及企业服务。</p>
    </div>
    <div class="platform loadding">
      <img class="second" src="../assets/img/about_us/platform.png" alt="" title="平台">
      <div class="txt">
        <p class="circle">为家庭提供便捷、高效、优质的家庭服务</p>
        <p class="circle">产品体系主要围绕家庭服务展开，充分考虑产品在设计</p>
        <p class="circle">家庭场景中的每一项物品，都有具体的服务要求</p>
        <p class="circle">多种套餐，满足不同家庭的多样化需求</p>
      </div>
    </div>
  
    <!--优势-->
    <div class="superiority loadding">
      <img src="../assets/img/about_us/superiority.png" alt="" title="优势">
      <img class="youshi" src="../assets/img/about_us/youshi.png" alt="" title="优势">
      <div class="txt">
        <p class="circle">强大的后台技术团队和品牌宣传团队</p>
        <p class="circle">成熟专业的技术、市场、管理和运营团队。</p>
        <p class="circle">完善的线上体系，从PC端到移动端，从前台展示到后台服务系统</p>
        <p class="circle">未来，服务需求市场广大</p>
      </div>
    </div>
  
    <!--服务者-->
    <div class="server loadding">
      <img src="../assets/img/about_us/server.png" alt="" title="服务者">
      <div class="txt">
        <p class="circle">我们专注地服务于注重生活品质的中高端人群， 帮他们从繁杂的家务中解放出来，让他们有更 多的时间去打拼事业，去陪伴家人</p>
        <p class="circle">我们致力于提高中小企业的后勤服务体验，提 高高品质、高效率、低成本的一站式整体服务， 让企业后勤更高效，办公更愉悦。</p>
      </div>
    </div>
    <!--底部-->
    <div class="plat-thingk loadding">
      <img src="../assets/img/about_us/ft2x.png" alt="" title="平台理念">
      <div class="txt1">
        <p>经营理念——诚实守诺质量为本合作共赢</p>
        <p>工作理念——倾听思考提问互助共进</p>
        <p>服务理念——用心交流真诚第一微笑服务</p>
        <p>管理理念——执行第一不畏权威以人为本</p>
      </div>
      <div class="txt2">
        <p>上下同心协力，忠实于公司事业。</p>
        <p>不断开拓，走在时代潮流的最前沿。</p>
        <p>力戒华而不实，力求朴实稳健。</p>
        <p>发扬温情友爱的精神，以公司为家，相亲相爱。</p>
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
  .loadding img {
    z-index: 0;
  }
  
  .about1 {
    background-color: #fff;
    padding-bottom: 1.92rem;
  }
  
  .about {

    position: relative;
    z-index: 5;
    p {
      position: absolute;
      top: 41.466666%;
      left: 20px;
      width: 7rem;
      font-size: .48rem;
      line-height: .64rem;
      text-indent: 2em;
      color: #ffffff;
    }
    .first {
      min-height: 14rem;
    }
    .us {
      position: absolute;
      top: 10.13333%;
      left: 20px;
      width: 4.26rem;
    }
  }
  
  //platform
  .platform {
    position: relative;
    margin-top: -21.4%;
    .second {
      min-height: 6rem;
    }
    img {
      background-color: #fff;
    }
  }
  
  .txt {
    position: absolute;
    top: 50%;
    left: .8rem;
    p {
      position: relative;
      font-size: .44rem;
      line-height: .44rem;
      color: #ffffff;
      padding-left: 10px;
      margin-bottom: .64rem;
    }
    .circle::before {
      position: absolute;
      left: 0;
      top: 50%;
      margin-top: -3px;
      content: "";
      width: 6px;
      height: 6px;
      background-color: #fff;
      -webkit-border-radius: 50%;
      -moz-border-radius: 50%;
      border-radius: 50%;
    }
  }
  
  //优势
  .superiority {
    position: relative;
    .youshi {
      position: absolute;
      width: 5.18rem;
      top: -1.26rem;
      right: .5rem;
    }
    .txt {
      p {
        color: #000;
      }
      .circle::before {
        background-color: #000;
      }
    }
  }
  
  .server {
    position: relative;
    .txt {
      top: 34.39%;
      width: 9.32rem;
      p {
        line-height: .68rem;
      }
      .circle::before {
        top: .34rem;
      }
    }
  }
  
  .plat-thingk {
    position: relative;
    .txt1,
    .txt2 {
      position: absolute;
    }
    p {
      font-size: .44rem;
      line-height: .84rem;
      color: #2c2c2c;
    }
    .txt1 {
      top: 2.4rem;
      right: .5rem;
    }
    .txt2 {
      left: .6rem;
      bottom: 1.12rem;
    }
  }
</style>
