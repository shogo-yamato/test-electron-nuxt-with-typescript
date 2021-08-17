<template>
  <div class="other-page-container">
    <h1 class="title">ページです</h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({});
</script>

<style lang="scss" scoped>
.other-page-container {
  width: 100vw;
  height: calc(100vh - 50px);
  background-color: pink;

  > .title {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100%;
    font-size: 10rem;
  }
}
</style>
