<template>
  <div>
    <h1>home</h1>
    <div id="search">
      <TwitterSearchBox />
    </div>
    <div id="result">
      <TwitterResultList />
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
