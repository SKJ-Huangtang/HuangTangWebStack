<template>
  <div class="home">
    <a href="https://go.huangtang.link/"><img alt="Vue logo" src="../assets/logo.png"></a>
    <HelloWorld msg="Welcome to HuangTang's bookmarks"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
};
</script>
