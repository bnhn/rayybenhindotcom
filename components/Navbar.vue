<template>
    <nav class="breadcrumb is-medium has-bullet-separator" role="navigation" aria-label="main navigation">
      <ul>
        <li>
          <nuxt-link class="navbar-item item" to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link class="navbar-item item" to="/projects">Projects</nuxt-link>
        </li>
      </ul>
    </nav>
</template>

<style scoped>
nav {
  font-size: 1.2rem;
  color: #111;
}

ul {
  margin-left: 1rem;
}
a {
  color: inherit;
}
.item:hover {
  text-decoration: underline;
  background-color: inherit;
  color: inherit;
}
</style>

