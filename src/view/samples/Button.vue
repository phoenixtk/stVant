<template>
<div>
  <van-button type="default">默认按钮</van-button>
  <van-button type="primary">主要按钮</van-button>
  <van-button type="warning">警告按钮</van-button>
  <van-button type="danger">危险按钮</van-button>
</div>
</template>

<script>
import {
  Button
} from 'vant';

export default {
  components: {
    [Button.name]: Button
  },

  data() {
    return {

    };
  },

  methods: {
    sorry() {
        
    }
  }
};
</script>

<style lang="less">

</style>
