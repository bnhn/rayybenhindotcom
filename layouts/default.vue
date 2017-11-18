<template>
  <div>
    <navbar></navbar>
    <nuxt/>
  </div>
</template>

<script>
import Navbar from '../components/Navbar'
export default {
  components: {
    Navbar
  }
}
</script>


<style>
html {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-size: calc(1rem + 0.5vw);
  font-family: "Source Sans Pro", "Helvetica Neue", Arial, sans-serif;
  font-weight: 400;
  color: #111;
}
</style>
