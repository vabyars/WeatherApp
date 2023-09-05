<script setup lang="ts">

import CitySearch from "./CitySearch/CitySearch.vue";
</script>

<template>
	<div class="weather-summary">
		<CitySearch />
		<div>
			Тут будет иконка погоды
		</div>

		<div>
			<h3>15 градусов</h3>
			<span> Облачно с прояснениями</span>
		</div>
		
		<hr>

		<div>
			<span>location</span>
			<span>current date</span>
		</div>
	</div>
</template>

<style scoped lang="sass">
	@import "WeatherSummary"
</style>