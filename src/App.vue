<script>


import weatherInfo from "./components/weatherInfo.vue";
import locationMap from "./components/locationMap.vue";

  export default {

    components: {
      
      locationMap,
      weatherInfo
        
    },

  }

</script>

<template>

  <locationMap></locationMap>
  <weatherInfo></weatherInfo>
  
</template>

<style lang="scss">

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  display: flex;
  height: 100vh;
  overflow: hidden;
}

</style>
