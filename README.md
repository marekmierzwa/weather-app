# Weather App

Create application which contains of:

1. Search input where user can type location (like city London, Krakow etc.). Submitting search should make a
call using [https://geocoding-api.open-meteo.com/v1/search?name=location](https://geocoding-api.open-meteo.com/v1/search?name=location) (where `location` is text typed by user)

2. Results from the call should show as a list below search input

3. Clicking on any result item should trigger a call to [Open Meteo API](https://open-meteo.com/en) and on
success response current temperature in clicked location should be shown.

