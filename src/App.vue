<template>
  <div id="app">
      <div class="flex">{{ someData }}</div>
  </div>
</template>

<script>
export default {
    name: 'app',
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