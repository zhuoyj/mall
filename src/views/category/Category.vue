<template>
  <h2>分类</h2>
</template>

<script>
import BScroll from "better-scroll";
export default {
  name: "Category",
  data() {
    return {
      scroll: null,
    };
  },
  //组件创建完后调用
  created() {
    // this.scrool = new BScroll(".wrapper");
  },
  mounted() {
    this.scroll = new BScroll(".wrapper", {
      probeType: 3,
    });

    this.scroll.on("scroll", (position) => {});
  },
};
</script>

<style scoped>
</style>
