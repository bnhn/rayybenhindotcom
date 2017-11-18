<template>
  <div class="container">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <div class="navbar-items navbar-start">
          <nuxt-link class="navbar-item item" to="/">Home</nuxt-link>
          <span class="navbar-item">|</span>
          <nuxt-link class="navbar-item item" to="/projects">Projects</nuxt-link>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>
div > .navbar-items {
  font-size: 1.2rem;
  display: inline-block;
}
.item:hover {
  text-decoration: underline;
  color: inherit;
}
</style>

