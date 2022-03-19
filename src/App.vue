<template>
  <v-app>
    <v-main>
      <HelloWorld/>
      <WeatherCard/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import WeatherCard from './components/WeatherCards'

export default {
  name: 'App',

  components: {
    HelloWorld,
    WeatherCard
  },

  data: () => ({
    //
  }),
}
</script>
