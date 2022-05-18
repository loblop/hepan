<template>
  <div class="home">
    <h1>title</h1>
    <tou></tou>
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import tou from '@/components/tou.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    tou
  }
}
</script>
