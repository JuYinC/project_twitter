<template>
  <div class="container">
    <div class="item search-box">
      <TwitterSearchBox />
    </div>
    <div class="item result-list">
      <TwitterResultList />
    </div>
  </div>
</template>

<style lang="scss">
@import "/assets/index.scss";
</style>

<script>
export default {
  name: "IndexPage",
};
</script>