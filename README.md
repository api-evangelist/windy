# Windy (windy)

Windy.com is a weather visualization platform serving high-resolution forecast models, animated weather maps, and a global webcam network. The Windy API exposes three developer products - a Point Forecast API for multi-model numerical weather data at a coordinate, an embeddable Map Forecast API based on Leaflet, and a Webcams API for the world's largest webcam repository.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/windy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/windy/refs/heads/main/apis.yml)

## Tags

- Weather
- Forecast
- Maps
- Webcams
- Visualization

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Windy Point Forecast API

A single POST endpoint that returns multi-model numerical weather forecast data (temperature, wind, precipitation, clouds, pressure, waves, air quality and more) for a latitude/longitude across weather, sea, and air-quality models such as GFS, ICON, AROME, NAM, and CAMS.

- **Human URL:** [https://api.windy.com/point-forecast/docs](https://api.windy.com/point-forecast/docs)
- **Base URL:** `https://api.windy.com/api/point-forecast/v2`

#### Tags

- Weather
- Forecast
- Point Forecast
- Numerical Weather Prediction

#### Properties

- [Documentation](https://api.windy.com/point-forecast/docs)
- [OpenAPI](openapi/windy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/windy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/windy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windy Map Forecast API

An embeddable JavaScript map library based on Leaflet 1.4.x that renders animated Windy weather layers, particles, isolines, and interactive controls in a web or mobile app, bootstrapped from libBoot.js and configured with a Windy API key.

- **Human URL:** [https://api.windy.com/map-forecast/docs](https://api.windy.com/map-forecast/docs)
- **Base URL:** `https://api.windy.com/assets/map-forecast/libBoot.js`

#### Tags

- Weather
- Maps
- Leaflet
- Visualization
- Embeddable

#### Properties

- [Documentation](https://api.windy.com/map-forecast/docs)
- [Source Code](https://github.com/windycom/API)
- [OpenAPI](openapi/windy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Windy Webcams API

A REST API providing access to the world's largest repository of webcams, with list and detail endpoints filterable by location, category, and country, each webcam carrying preview images, timelapse players, and location metadata. Authenticated with an x-windy-api-key header.

- **Human URL:** [https://api.windy.com/webcams/docs](https://api.windy.com/webcams/docs)
- **Base URL:** `https://api.windy.com/webcams/api/v3`

#### Tags

- Webcams
- Imagery
- Timelapse
- Geolocation

#### Properties

- [Documentation](https://api.windy.com/webcams/docs)
- [OpenAPI](openapi/windy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/windy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/windy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/windycom)
- [LinkedIn](https://www.linkedin.com/company/windy-com)
- [Website](https://www.windy.com)
- [Documentation](https://api.windy.com)
- [Plans](plans/windy-plans-pricing.yml)
- [Rate Limits](rate-limits/windy-rate-limits.yml)
- [Fin Ops](finops/windy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
