<template>
  <div id="app">
    <HelloWorld />
    <LibComponentOne />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import { LibComponentOne } from 'vue-library-sample'

export default {
  name: 'app',
  components: {
    HelloWorld,
    LibComponentOne
  }
}
</script>
