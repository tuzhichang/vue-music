<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <player></player>
  </div>
</template>

<script>
  import MHeader from 'components/header/m-header'
  import Player from 'components/player/player'
  import tab from 'components/tab/tab'
  export default {
    components: {
      MHeader,
      Player,
      tab
    }
  }
</script>

<style lang="scss" scoped>
</style>
