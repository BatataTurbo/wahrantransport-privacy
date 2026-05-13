# Privacy Policy for Wahran Transport

Last updated: 2026-05-13

Wahran Transport is an independent transit guide application for Oran, Algeria. This policy explains what data the app uses, what may be sent to the Wahran Transport backend, and what is not collected.

## 1. Data stored on the device

The app may store the following data locally on your device:

- Favorite lines and favorite stations selected by you
- Favorite addresses saved by you
- Recent trip previews, so you can reopen recent routes
- Interface and station-language preferences
- Your analytics consent choice

This local data remains on your device unless you delete it, clear app storage, or uninstall the app.

## 2. Location data

Location is optional. The app asks for location only when you use a location-based feature such as the current-location button. The app does not request background location.

When you use current location, a map pin, or an address as part of route planning, the route request may include the origin and destination coordinates needed to calculate the route. Exact location is not used to create an account profile and is not sold to advertisers.

## 3. Route and search requests

To calculate routes and search for addresses or places, the app communicates with the Wahran Transport backend.

Route requests may include:

- Origin and destination types, such as station, address, GPS pin, or map click
- Coordinates or station identifiers needed to calculate the route
- Route preference, such as fastest or fewer transfers
- App version code

Search requests may include the text typed by the user in the search field. The backend first searches server-side local data for Oran and may use an external geocoding fallback only when local results are not sufficient.

## 4. Optional analytics

If you accept analytics, the app may send anonymized and aggregated usage events to help improve the transport network and the app.

Analytics may include:

- Popular origin and destination zones
- Whether a route was found
- Lines used in calculated routes
- Transfer count, walking-distance bucket, and duration bucket
- Route preference and origin/destination type
- Feedback submitted by the user about route quality
- Technical API usage counters, such as endpoint, status, cache status, and provider

Analytics does not include an account name, phone number, email address, advertising ID, or precise device identifier. Exact GPS coordinates are not stored in analytics tables; route locations are converted to readable zones or rounded approximate zones for analysis.

You can change your analytics choice in the app's About screen.

## 5. Third-party services

The app and backend may rely on third-party services:

- Cloudflare: backend hosting, cache, object storage, and analytics database
- OpenStreetMap contributors: map and geocoding source data
- MapLibre: map rendering library
- OpenFreeMap or another configured map tile provider: background map tiles
- Photon: optional geocoding fallback based on OpenStreetMap data when local search has no result
- Android operating system location services: device location permission and location retrieval

The public Nominatim service is not used for autocomplete in the production configuration.

Third-party providers may process technical request data such as IP address according to their own terms and privacy policies.

## 6. OpenStreetMap attribution and ODbL

Some map and search data is based on OpenStreetMap. OpenStreetMap data is copyright OpenStreetMap contributors and available under the Open Database License (ODbL). Required attribution is displayed in the app and in the open-source notices.

The proprietary transit compilation used by Wahran Transport is separate from OpenStreetMap data. OpenStreetMap rights and obligations remain governed by the OpenStreetMap license.

## 7. Sharing

Wahran Transport does not sell personal data to advertisers or data brokers.

The publisher may share anonymized and aggregated transport insights with public authorities, transport operators, or urban-planning partners, for example popular corridors, peak hours, underserved zones, and route-quality indicators. These reports are intended to improve public transport planning and should not identify individual users.

## 8. Retention and deletion

Local favorites and recent trips remain on the device until deleted by the user, app storage is cleared, or the app is uninstalled.

Aggregated analytics may be retained as long as needed to improve the service, monitor abuse, and prepare transport-planning reports. Because the app does not use accounts, the publisher generally cannot link server-side analytics rows to a specific named person.

## 9. Security

The app uses Android app sandboxing and release hardening features such as code shrinking and non-debuggable release builds. The backend uses authentication, rate limits, caching, and daily soft caps to reduce abuse. No security measure can guarantee absolute protection.

## 10. Contact

- Publisher name: Wahran Transport
- Contact email: transportalgerien@protonmail.com
