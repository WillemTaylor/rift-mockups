<template>
  <div id="app">
    <Header />
    <Title />
    <ClaimRefund />
  </div>
</template>

<script>
import Header from "./components/header";
import Title from "./components/title";
import ClaimRefund from "./components/claim-refund";

export default {
  name: "App",
  components: {
    Header,
    Title,
    ClaimRefund
  }
};
</script>

<style lang="scss">
@import "./assets/styles.scss";
</style>
