<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->

    <Report />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

import Report from '@/components/Report.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    Report
  }
}
</script>
