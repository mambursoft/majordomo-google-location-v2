# Google Connection v2

Experimental v2 package by mambursoft. Published separately from the earlier Google Location v2 listing.

## Status

- separate marketplace package with the v2 suffix;
- install instead of the previous Google Location module, not alongside it;
- source module folder remains `modules/google_location` for compatibility.

## Architecture

1. Presentation: templates and responsive map layout with light/dark tokens.
2. Application: module class coordinates settings, users and map view.
3. Domain: location users, battery/charging state, object binding and forwarding rules.
4. Infrastructure: Google session client, optional Geocoding API, GPS Tracker bridge.

## Manual

Open Control Panel -> Google Connection v2 -> Manual, or read `docs/MANUAL.md`.

## Localization

English, Russian, Ukrainian (ua/uk alias).