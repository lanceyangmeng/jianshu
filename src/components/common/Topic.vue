<template>
    <div class="recommend-collection">
      <a class="collection" v-for="topic in topicList" :key="topic.id">
        <router-link :to="'/c/'+topic.id">
          <img :src="topic.topicUrl" class="small-img">
          <div class="name more">{{topic.topicName}}</div>
        </router-link>
      </a>
      <router-link to="/collections">
        <span class="more">更多热门专题></span>
      </router-link>
    </div>
</template>

<script>
    export default {
        name: "Topic",
      data() {
        return {

    }
</script>

<style scoped>
div{
  display: inline-block;
  padding: 0 11px 0 6px;
  margin-top: 10px;
  font-size: 14px;
  color: black;
}
  .collection{
    margin-left: 40px;
    margin-top: 10px;

  }
  .collection img{
    width: 30px;
    height: 30px;
  }
</style>
