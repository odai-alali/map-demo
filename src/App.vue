<template>
  <div id="app">
    <awesome-map :mapData='mapData'></awesome-map>
  </div>
</template>

<script>
import AwesomeMap from './components/AwesomeMap'
import {mapData} from './data'
export default {
  name: 'app',
  data () {
    return {
      mapData: mapData
    }
  },
  components: {
    AwesomeMap
  }
}
</script>

<style>
html, body {
  margin:0;
  padding: 0;
  width: 100%;
  height: 100%;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex: 1;
  height: 100%;
}

</style>
