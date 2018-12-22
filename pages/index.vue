<template>
  <main>
    <Hero/>
    <section id="stylists" class="section stylists">
      <h2 class="section-title">Stylists</h2>
      <div class="container">
        <div class="columns is-multiline">
          <div class="column is-one-third">
            <profileCard/>
          </div>
          <div class="column is-one-third">
            <profileCard/>
          </div>
          <div class="column is-one-third">
            <profileCard/>
          </div>
          <div class="column is-one-third">
            <profileCard/>
          </div>
          <div class="column is-one-third">
            <profileCard/>
          </div>
          <div class="column is-one-third">
            <profileCard/>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
  import Hero from '~/components/Hero.vue'
  import profileCard from '~/components/profileCard.vue'

  export default {
    components: {
      Hero,
      profileCard
    }
  }
</script>

<style lang="scss">
  .stylists {
    padding-bottom: 9rem;
    
    .column {
      padding: 1.25rem;
    }
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
