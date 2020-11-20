<template>
  <body>
    <div class="container">
      <div>
        <Logo />
        <h1 class="title">
          first-nuxt-project
        </h1>
        <div class="links">
          <NuxtLink
            to="/index2"
            rel="noopener noreferrer"
            class="button--green"
          >
            Dark
          </NuxtLink>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.dark{
  background: #35495e;
}
.dark .title, .dark .subtitle{
  color: #fff;
}
.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
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
