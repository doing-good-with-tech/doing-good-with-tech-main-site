<template>
  <div id="app">
    <Header />
    <Description />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Description from "./components/Description.vue";

export default {
  name: "app",
  components: {
    Header,
    Description
  }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Nunito|Open+Sans");
* {
  padding: 0;
  margin: 0;
}
html {
  width: 100%;
  height: 100%;
  body {
    width: 100%;
    height: 100%;
    #app {
      width: 100%;
      height: 100%;
      font-family: "Open Sans", sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      color: #3b413c;
      background-color: #f7f9f7;
      h1 {
        font-family: "Nunito", sans-serif;
      }
    }
  }
}
</style>
