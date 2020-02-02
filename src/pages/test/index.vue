<template>
  <div>
    <!-- 文本格式 Mustach-->
    <span>学习课程{{className}}</span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      className: 'mpvue 学习'
    };
  }
};
</script>

<style>
</style>