<template>
  <div class="home_container">
    <itemContainer father-component="home"></itemContainer>
  </div>
</template>

<script>
  import itemContainer from '../../components/itemContainer'

  export default {
    name: 'home',
    components: {
      itemContainer
    },
    created() {
    }
  }
</script>

<style lang="less" scoped>
  .home_container {
  }
</style>
