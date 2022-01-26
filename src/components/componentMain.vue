<template>
  <div>
      <h1>Hello</h1>
      <insideMain/>
  </div>
</template>

<script>

import insideMain from './insideMain.vue'

export default {
  name: 'componentMain',
  components: {
    insideMain
  }
}
</script>

<style scoped lang="scss">

h3 {
  margin: 40px 0 0;
}

</style>
