<template>
  <div id="app">
    <!-- Header -->
    <Header />

    <!-- Main -->
    <div id="main" role="main">
      <router-view></router-view>
    </div>

    <!-- Footer -->
  </div>
</template>

<script>
import Header from '@/components/Header'

export default {
  components: {
    Header
  }
}
</script>

<style lang="scss">
#app {
  #main {
    margin-top: 80px;
  }
}
</style>
