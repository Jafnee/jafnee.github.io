<template>
  <div>
    <nuxt/>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.links a {
  margin: 0 5px;
}

.button--li {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #0576b5;
  color: #0576b5;
  text-decoration: none;
  padding: 10px 30px;
}

.button--li:hover {
  color: #fff;
  background-color: #0576b5;
}

.button--gh {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #333;
  color: #333;
  text-decoration: none;
  padding: 10px 30px;
}

.button--gh:hover {
  color: #fff;
  background-color: #333;
}

.button--gm {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #dd4b39;
  color: #dd4b39;
  text-decoration: none;
  padding: 10px 30px;
}

.button--gm:hover {
  color: #fff;
  background-color: #dd4b39;
}

.button--projects {
  opacity: .5;
  cursor: default;
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #dd4b39;
  color: #dd4b39;
  text-decoration: none;
  padding: 10px 30px;
}

.button--projects:hover {
  color: #fff;
  background-color: #dd4b39;
}
</style>
