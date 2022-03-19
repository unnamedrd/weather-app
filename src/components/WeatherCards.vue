<template>
    <v-card
    class="mx-auto"
    max-width="344"
    >
    <v-card-header-text>
      <v-card-title>Monday</v-card-title>

      <v-card-subtitle>Forecast</v-card-subtitle>
    </v-card-header-text>
    </v-card>
</template>

<script>
export default {
   name: 'WeatherCard',
   data: ()=>({
       show: false,
   }),
}
</script>