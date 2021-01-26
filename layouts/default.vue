<template>
  <main class="container relative min-h-screen pt-16">
    <Header />
    <nuxt />
  </main>
</template>

<script>
  import Header from '~/components/Header'
  import Fff from '~/components/Fff'

  export default {
    components: {
      Header,
      Fff
    }
  }
  </script>