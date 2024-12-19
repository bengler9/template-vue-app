<template>
  <section class="notfound">
    <base-card>
      <h1>Page Not Found</h1>
      <p>
        The requested page could not be found. Maybe take a look at our
        <router-link to="/home">main screen</router-link> for more info.
      </p>
    </base-card>
  </section>
</template>

<style scoped>
@media (min-width: 1024px) {
  .notfound {
    min-height: 40vh;
    display: flex;
    align-items: center;
  }
}
</style>
