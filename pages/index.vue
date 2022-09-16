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
// import Client from "twitter-api-sdk";
export default {
  name: "IndexPage",
  methods: {},
  // async mounted() {
  //   const client = new Client(process.env.BEARER_TOKEN);
  //   const tweet = await client.tweets.findTweetById("20");
  //   console.log(tweet.data.text);
  // },
};
</script>