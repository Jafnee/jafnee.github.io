<template>
  <section class="container">
    <div>
      <h1 class="title">
        Jafnee Jesmee
      </h1>
      <h2 class="subtitle">
        Things... coming soon
      </h2>
      <div class="links">
        <a
          href="https://github.com/jafnee"
          target="_blank"
          class="button--gh">GitHub</a>
        <a
          href="https://www.linkedin.com/in/jafnee/"
          target="_blank"
          class="button--li">LinkedIn</a>
        <a
          title="Coming soon"
          class="button--projects">Projects</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
