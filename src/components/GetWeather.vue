<template>
    <div>
        {{data}}
    </div>
</template>

<script>
export default {
    name: "App", 
    data(){
        return {
            data:{}
        }
    },

    beforeMount(){
        await this.getForecast();
    },
    methods: {
        async getForecast(){
            const response = await fetch(http:api.openweathermap.org/data/2.5/forecast?id=524901&appid={API key});
            const data = await.response.json();
            this.data = data;
        }
    }
}
</script>