<template>
  <div>
    <h1>home</h1>
    <h1>{{ appName }}</h1>
    <HelloWorld msg="Hello world" />
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  b: '{{appName}}',
  components: {
    HelloWorld,
  },
};
</script>

<style lang="scss" scoped></style>
