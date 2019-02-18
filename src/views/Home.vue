<template>
  <div class="home">
    home-123-123
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />

    <div class="vux-wrap">
      <x-button>vux-submit</x-button>
      <x-button type="primary">vux-primary</x-button>
      <x-button type="warn">vux-Delete</x-button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import { XButton } from "vux";

export default {
  name: "home",
  components: {
    HelloWorld,
    XButton
  }
};
</script>

<style lang="less">
.vux-wrap {
  position: relative;
  width: 600px;
}
</style>
