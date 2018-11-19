<template>
  <div class="home">
    hello
    <el-button>默认按钮</el-button>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue';
  // import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
  import axios from 'axios'
  
  export default Vue.extend({
    name: 'home',
    components: {
      // HelloWorld,
    },
    created() {
      axios.post('http://test-m.ufxin.com/baseapi/yluser_info?userid=1336')
        .then(function(response) {
          console.log(response);
        })
        .catch(function(error) {
          console.log(error);
        });
    },
    destroyed(){
      console.log('over')
    }
  });
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  
</style>
