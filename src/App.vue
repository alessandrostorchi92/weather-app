<script>


import weatherForecastInfo from "./components/weatherForecastInfo.vue";
import locationMap from "./components/locationMap.vue";

  export default {

    components: {
      
      locationMap,
      weatherForecastInfo
        
    },

  }

</script>

<template>

      <div class="headline-container">
        <p class="headline">Plan you future with confidence</p>
      </div>
  
      <div class="show-map-container">
        <button class="show-map-btn">SHOW MAP</button>
      </div>
    
    <locationMap></locationMap>
    <weatherForecastInfo></weatherForecastInfo>
  
</template>

<style lang="scss">

.headline {
  font-family: "Unbounded", sans-serif;
  font-optical-sizing: auto;
  font-weight: 300;
  font-style: normal;
  color: #faf0e6;
  font-size: 2.5rem;
  text-wrap: balance; 
  padding-bottom: 4rem;
}

.headline-container, .show-map-container {
  text-align: center;
}

.show-map-btn {
    background-color: transparent;
    border: 2px solid #faf0e6;
    color: #faf0e6;
    padding: 1.6rem;
    font-size: 1.2rem;
    font-weight: bolder;
    letter-spacing: 0.8rem;
    font-family: "Cinzel", serif;
    font-optical-sizing: auto;
    font-style: normal;
    border-radius: 50px;   
    cursor: pointer;
    transition: transform 0.4s ease-out;
}

.show-map-btn:hover {
    transform: scale(1.2);
}


</style>
