<template>
  <div>
    {{ data }}
  </div>
</template>
<script lang="ts" setup>
const data = await useFetch("https://localhost:7167/WeatherForecast");
</script>
