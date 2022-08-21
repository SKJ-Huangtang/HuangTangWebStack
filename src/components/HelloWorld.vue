<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      <br>
      <br>
      This is a tool page<br>
      For more information, please click on this pages:
      <br>
      <a href="http://blogs.huangtang.link/" target="_blank" rel="noopener">HuangTang的博客</a>
      &ensp;or&ensp;
      <a href="http://175.24.152.246:3000/#/" target="_blank" rel="noopener">HuangTang的记事本</a>
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
a {
  color: #42b983;
}
</style>
