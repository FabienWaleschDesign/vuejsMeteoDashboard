<template>

  <main class="home-page">
    <section id="search-bar">
      <form action="post" method="post">
        <input type="text" name="city-request" id="city-request" placeholder="Tape your City request here">
        <div class="button" type="submit">
          <p>Send</p>
          <i class="material-icons md-18">send</i>
        </div>
      </form>
    </section>
    <section id="main-request">
      <div class="screen">
        <p>Hello World!</p>
      </div>
    </section>
    <section id="meteo-prev">
      <div class="screen">
        <p>Hello World!</p>
      </div>
    </section>
  </main>

</template>

<script>
  export default  {
    name: 'home-page',
    props: [],
    mounted() {

    },
    data() {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}
</script>

<style scoped lang="scss">
</style>
