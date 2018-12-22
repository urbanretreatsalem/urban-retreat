<template>
  <div>
    <Navbar/>
    <nuxt/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>

<style>
  body, button, input, select, textarea {
    font-family: Montserrat, BlinkMacSystemFont, -apple-system, "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Fira Sans", "Droid Sans", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
    color: #444;
  }

  .page-title {
    font-size: 4rem;
    font-weight: 300;
    color: #444;
  }

  .section-title {
    text-align: center;
    font-size: 4rem;
    font-weight: 300;
    letter-spacing: .015em;
    margin-bottom: 3rem;
    margin-top: 3rem;
    color: #444;
  }


</style>
