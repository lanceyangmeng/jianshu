<template xmlns:src="http://www.w3.org/1999/xhtml">
  <b-row>
    <b-col cols="8">
      <v-carousel></v-carousel>
      <!--<div class="recommend-collection">-->
        <!--&lt;!&ndash;<div class="btn-group" role="group" aria-label="...">&ndash;&gt;-->
        <!--<button type="button" class="btn btn-default" >Left</button>-->
        <!--</div>-->
      <!--</div>-->
      <div style="font-size: 10px">
        <a class="collection btn btn-default btn btn-default " target="_blank" href="/c/1" type="button">
          <img width="35" height="35" src="//upload.jianshu.io/collections/images/76/12.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/64/h/64" alt="64">
          自然科普
        </a>
        <a class="collection btn btn-default" target="_blank" href="/c/2" type="button">
          <img width="35" height="35" src="//upload.jianshu.io/collections/images/83/1.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/64/h/64" alt="64">
        摄影
        </a>

        <a class="collection btn btn-default" target="_blank" href="/c/3" type="button">
        <img width="35" height="35" src="//upload.jianshu.io/collections/images/95/1.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/64/h/64" alt="64">
        故事
        </a>

        <a class="collection btn btn-default" target="_blank" href="/c/4" type="button">
        <img width="35" height="35" src="//upload.jianshu.io/collections/images/4/sy_20091020135145113016.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/64/h/64" alt="64">
        读书
        </a>

        <a class="collection btn btn-default" target="_blank" href="/c/5" type="button">
        <img width="35" height="35" src="//upload.jianshu.io/collections/images/14/6249340_194140034135_2.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/64/h/64" alt="64">
        @IT·互联网
        </a>

        <a class="collection btn btn-default" target="_blank" href="/c/6" type="button">
        <img width="35" height="35" src="//upload.jianshu.io/collections/images/21/20120316041115481.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/64/h/64" alt="64">
        简书电影
        </a>

        <a class="collection btn btn-default" target="_blank" href="/c/7" type="button">
        <img width="35" height="35" src="//upload.jianshu.io/collections/images/13/%E5%95%8A.png?imageMogr2/auto-orient/strip|imageView2/1/w/64/h/64" alt="64">
        <!--<div class="name">旅行·在路上</div>-->
          旅行·在路上
        </a>

        <a class="more-hot-collection btn btn-default" target="_blank" href="/collections" type="button">
          更多热门专题
          <i class="iconfont ic-link"></i>
        </a>
      </div>
      <v-article></v-article>
    </b-col>
    <b-col>
      <v-right></v-right>
    </b-col>
  <b-col>
    <a href="#" class="btn btn-default" style="position:fixed;right:20px;bottom:20px"><b-img src="../../static/img/top.png"/></a>
    <!--<a class="btn btn-default" href="#" role="button" style="position:fixed;right:0;bottom:0">回到顶部</a>-->
  </b-col>
  </b-row>
</template>

<script>
  import vCarousel from '../common/Carousel';
  import vArticle from '../common/Article';
  import vRight from '../common/Right';
  import 'bootstrap/dist/css/bootstrap.css'
  import 'jquery/dist/jquery.min'
  import 'bootstrap/dist/js/bootstrap.min'

  export default {
    name: "Index",

    components: {
      vCarousel,
      vArticle,
      vRight
    }
  }
</script>

<style scoped>
  .back_to_top{
    position: fixed;
    bottom:30px;
    right: 30px;
    border:1px solid #888;
  }
</style>
