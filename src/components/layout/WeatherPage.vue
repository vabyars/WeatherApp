<script setup lang="ts">

import WeatherSummary from "./WeatherSummary/WeatherSummary.vue";
import TodayHighlights from "./TodayHighlights/TodayHighlights.vue";
import CoordinatesInfo from "./Coordinates/CoordinatesInfo.vue";
import HumidityInfo from "./Humidity/HumidityInfo.vue";
</script>

<template>
	<div class="page">
		<WeatherSummary />

		<TodayHighlights />

		<CoordinatesInfo />

		<HumidityInfo />
	</div>
</template>

<style scoped lang="sass">
	@import "WeatherPage"
</style>