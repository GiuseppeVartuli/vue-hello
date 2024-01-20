<script>
export default {
  name: "App",
  data() {
    return {
      player: "John Terry",
      img: "https://static.fctables.com/upload/w6/w6o5z58bef68f1cf81/john-terry.png",
    };
  },
};
</script>

<template>
  <h1>{{ player }}</h1>
  <div>
    <img :src="img" alt="" />
  </div>
</template>

<style></style>
