<template>
  <div class="awesome-map">
        <gmap-map :center="{lat:1.38, lng:103.8}" :zoom="12">
          <!-- <gmap-marker :position="{lat:1.38, lng:103.8}">
          </gmap-marker>
          <gmap-info-window :position="{lat:1.38, lng:103.8}">
            Hello world!
          </gmap-info-window> -->
        </gmap-map>
  </div>
</template>

<script>
  export default {
    props: [
      'mapData'
    ],
    mounted () {

    }
  }
</script>

<style>
.awesome-map {
    display: flex;
    flex: auto;
  }
  .vue-map-container {
    display: flex;
    flex: auto;
  }
</style>
