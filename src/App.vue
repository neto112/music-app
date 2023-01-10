<template>
  <div class="app-container p-3 bg-black m-auto">
    <SongList />
  </div>
</template>

<script>
import SongList from './components/SongList.vue'

export default {
  name: 'App',
  components: {
    SongList
  }
}
</script>

<style>
.app-container {
  width: 350px;
  height: 700px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 20px;
}
</style>
