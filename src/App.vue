<template>
  <div id="app">
      <div class="flex">{{ someData }}</div>
      <SomeComponent />
  </div>
</template>

<script>
import SomeComponent from './components/SomeComponent.vue'

export default {
    name: 'app',
    components: {
        SomeComponent
    },
    data() {
        return {
            someData: 'it works'
        }
    }
}
</script>

<style lang="scss">
.flex {
    font-size: $font-size;
}
</style>