<template>
  <nav class="menu">
    <router-link to="/">Home</router-link>
    <router-link to="/contact-us">Contact Us</router-link>
    <router-link to="/portfolio">Portfolio</router-link>
  </nav>
</template>

<script>
export default {
    name: 'NavComponent'
}
</script>

<style lang="scss">
.menu {
    height: auto;
    display: flex;
    justify-content: center;
}
a {
    text-decoration: none;
    padding: 10px;
    vertical-align: middle;
}
</style>