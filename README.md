# Windy (windy)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
