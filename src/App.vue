<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>


export default {

  name: "app",

};
</script>

<style>

:root {
  --primary: #ff6eb1;
  --light: #e6e6e6;
}

* {
  box-sizing: border-box;
}

html,
body {
  height: 100%;
  overflow: hidden;
}

h1,
h2,
h3,
h4,
h5,
h6,
p,
figure,
form,
blockquote {
  margin: 0;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: normal;
}

ul,
ol,
li,
dl,
dd {
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, segoe ui, Roboto,
    helvetica neue, Arial, noto sans, sans-serif, apple color emoji,
    segoe ui emoji, segoe ui symbol, noto color emoji;
  color: #262626;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  overscroll-behavior: none;
}

#app {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  background-color: #fff;
  overflow: hidden;
}
</style>
