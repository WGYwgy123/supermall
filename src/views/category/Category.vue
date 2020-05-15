<template>
  <div class="wrapper">
  </div>
</template>

<script>
  import BScroll from "better-scroll";

  export default {
    name: "Category",
    data() {
      return {
         scroll: null
      }
    },
    //组件创建后调用
   /* mounted() {
      this.scroll = new BScroll(document.querySelector('.wrapper'), {
        /!*
        * probeType的默认值为0 表示不监听
        * 0和1都不监听
        * 2表示监听但是不监听惯性滚动
        * 3为都监听
        * *!/
        probeType: 3,
        pullUpLoad: true
      })

      this.scroll.on('scroll', (position) => {
        console.log(position);
      })

      this.scroll.on('pullingUp', () => {
        console.log('上拉加载更多');
      })
    },
    methods: {
      btnClick() {
        console.log('btnClick');
      }
    }*/
  }
</script>

<style scoped>
 .wrapper {
   height: 200px;
   overflow: hidden;
   background-color: red;
 }
</style>