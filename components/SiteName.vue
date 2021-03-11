<template>
  <div class="title-container">
    <h3>{{ title }}</h3>
  </div>
</template>

<script>
import { ref } from "@nuxtjs/composition-api";
export default {
  setup() {
    const title = ref("sg taxi toulouse");
    return { title };
  },
};
</script>

<style lang="css" scoped>
.title-container {
  background: #ffffff;
  border-left: solid 1px #707070;
  border-right: solid 1px #707070;
  height: 10vh;
  margin-left: 8vw;
  width: 20vw;
}
h3 {
  color: #000;
  font-weight: 600;
  text-transform: uppercase;
}
</style>
