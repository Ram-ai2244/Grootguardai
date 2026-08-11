# AI Crop Doctor

Demo-ready browser prototype for the crop image → diagnosis → weather → treatment timing flow.

## Run it

Open `index.html` in a modern browser, or serve this folder with any static web server. No build step or API key is required.

Live weather uses Open-Meteo when available; the app automatically falls back to its demo-safe forecast data when offline. The UI service boundaries in `app.js` (`ImageInput`, `DiseaseDiagnosis`, `WeatherService`, and `ActionTimingEngine`) are designed to be replaced with a production vision API and weather backend.
# Grootguardai
